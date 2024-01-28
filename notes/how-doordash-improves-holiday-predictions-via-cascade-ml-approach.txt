Notes: How DoorDash Improves Holiday Predictions via Cascade ML Approach

- Most of the foreasting problem are solved by ML approach such as XGBoost. So ARIMA is very outdated and I have not seen it being used in the industry. ARIMA can't take features.. and has stationary assumptions. 

- The problem they are solving is how to improve the overall demand forecasting accuracy by improving the holiday's demand forecasting. Doordash delivery take out foods so demand usually sharp drop in holidays

- Simple tree approach gives very bad perf because the holiday impact get averaged out on certain tree nodes thus accuracy on those holidays are bad. 

- The cascading approach:
	- Build Small Regression Model: you break the delivery to thousands of zones and you train thousands of simple regression model to predict the multiplier between certain holidays period and the periods (weeks) before that. 
		- e.g: "We run a linear regression with holiday dummies for each starting point-daypart pair in our data and calculate the holiday multipliers as the coefficients for the holiday dummies. For instance, we could have a multiplier of 1.5 for Thanksgiving Day in Springfield, Ill., implying that the order volume will decrease 50% week-over-week for that starting point at the given holiday-daypart pair."

	- Use Small Regression Model to pre-process the training data (labels) to smooth out those holidays' drops and then train the model. (E.g: The label on thansgiving week is 50mil orders, you use your mulplier to lift it up to 75mil orders to remove the holiday effect. and then add it back in post processing once you have the prediction)

	- Use Small Regression Model to post-process those days that are holidays, apply the multiplier on demand predictions on those holidays. 

- Additional reminder: Read the ML Design Pattern book (cascading is one of the pattern. So is rebalacning and re-framing. )
















