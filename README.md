# MLE_Resources
List out good resources for MLE study. E.g: Good blog post, good git repo for reading and hands on examples

## Good Git Repos: 
- [RecSysPapers - 推荐系统相关论文汇总](https://github.com/tangxyw/RecSysPapers) 
- [AI-RecommenderSystem-Implementations](https://github.com/qizhong19920114/AI-RecommenderSystem-Implementations): 王喆书里很多的 implementation 在这里
- [Algorithm-Practice-in-Industry](https://github.com/Doragd/Algorithm-Practice-in-Industry): Gordon Lee 整理
- [推荐系统论文、学习资料、业界分享](https://github.com/wzhe06/Reco-papers)： 王喆老师整理
- [recsys_model_pytorch_implementation](https://github.com/qizhong19920114/recsys_model_pytorch_implementation)
- [Recommender System Pytorch 实现](https://github.com/QikaiXu/Recommender-System-Pytorch/tree/main)
- [Fun-Rec](https://github.com/datawhalechina/fun-rec/tree/master/docs)
- [Gen AI Resources](https://github.com/wel3kxial/AIGC_Resources/)


## How To Read Paper:
1.  Before you even start, look for __existing blogs__ that summarize the paper. If you didn't find any, then good luck, the paper might not worth reading. 
2.  Really look for __what problem this paper is trying to solve__ (should be in the Abstract Section), and stop reading if the problem and the problem solution is not of your interest. Also be aware of the __problem definition, framing and assumptions__, because they might be different than what you are looking for. 
3.  Look into the result section and see how the evaluation metrics is defined and why this new solution is alledgely better
4.  Introduction Section should cover most of the background which is interesting to read.
5.  Related Section is sometimes just pointing to other papers, if some paper you saw many differnt times then you should read. But other than that don't read too deep into it.
6.  Don't read too much into the math? But maybe pay a bit more attention to the symbol definitions. 


## My Paper Collections: 
- [OG Two Tower Paper DSSM](papers/[CIKM2013]%20Learning%20Deep%20Structured%20Semantic%20Models%20for%20Web%20Search%20using%20Clickthrough%20Data.pdf)
- [[KDD2023] Rethinking the Role of Pre-ranking in Large-scale E-Commerce Searching System](papers/[KDD2023]%20Rethinking%20the%20Role%20of%20Pre-ranking%20in%20Large-scale%20E-Commerce%20Searching%20System.pdf) (Pre-Ranker 粗排)
- [[Google] Generative Information Retrieval (slides)](https://docs.google.com/presentation/d/19lAeVzPkh20Ly855tKDkz1uv-1pHV_9GxfntiTJPUug/edit#slide=id.g2584b5dafc1_0_905)
- [[Google] Learning Vision from Models Rivals Learning Vision from Data](https://arxiv.org/pdf/2312.17742.pdf)
- NeurlPS2023@谷歌 | 生成式检索推荐系统 [paper](https://arxiv.org/abs/2305.05065) [blog](https://mp.weixin.qq.com/s/_lBb1Kc2xINdvccDsD--uQ)
- 淘宝主搜：大模型在长尾Query改写召回上的实践 [paper](https://arxiv.org/pdf/2311.03758.pdf) [blog](https://mp.weixin.qq.com/s/99MfXYFbz8KpHHJS7K3UQg)
- Matryoshka Representation Learning - NeurIPS 2022 [paper](https://arxiv.org/abs/2205.13147) [blog](https://zhuanlan.zhihu.com/p/680273451) (Used in OpenAI?)

## My Blog Collections
- 双塔召回模型的前世今生 [[上篇](https://zhuanlan.zhihu.com/p/430503952)][[下篇](https://zhuanlan.zhihu.com/p/441597009)]
- [算法工程师如何应对做算法策略的不确定性；比如没效果，这时绩效怎么保证？](https://www.zhihu.com/question/519431659/answer/2381893430)
- [一个算法工程师的日常是怎样的？](https://www.zhihu.com/question/29692814/answer/1644279431)
- [如何解决离线和线上auc和线上点击率不一致的问题？](https://www.zhihu.com/question/305823078/answer/1627340815)
- [推荐精排中如何建模position bias？如何利用一些强bias特征，如”商品点击率“？](https://www.zhihu.com/question/441981206/answer/2351404272)
- [CTR和推荐算法有什么本质区别？](https://www.zhihu.com/question/341529083/answer/1629035133)
- [目前工业界常用的推荐系统模型有哪些？](https://www.zhihu.com/question/314773668/answer/2259594886)

## My Workshop and Tutorials Collections: 
- [Video Recsys Workshop 2023](https://videorecsys.com/)
- [[CVPR 2023] Recent Advances in Vision Foundation Models](https://vlp-tutorial.github.io/)
- [Full Stack Deep Learning Course](https://fullstackdeeplearning.com/spring2021/lecture-7/)
- [A Guide to User Behavior Modeling](https://blog.reachsumit.com/posts/2024/01/user-behavior-modeling-recsys/)
- [RecSys ML by Gaurav Chakravorty](https://www.youtube.com/@recsysml)

## My Book Collections:
- [Machine Learning Design Patterns](https://www.amazon.com/Machine-Learning-Design-Patterns-Preparation/dp/1098115783/ref=sr_1_1?crid=37W2FAR2PPETR&keywords=machine+learning+design+patterns&qid=1706471977&sprefix=machine+leanring+desin+%2Caps%2C560&sr=8-1)
- [Design Machine Learning System](https://www.amazon.com/Designing-Machine-Learning-Systems-Production-Ready/dp/1098107969/ref=sr_1_1?crid=10KEYUVV5792P&keywords=machine+learning+chip+huyen&qid=1706472049&sprefix=machine+learning+chip%2Caps%2C388&sr=8-1)
- [Machine Learning System Design Interview](https://www.amazon.com/Machine-Learning-System-Design-Interview/dp/1736049127/ref=sr_1_1?crid=2K7OZJG6DEZ2C&keywords=machine+learning+system+design&qid=1706472036&sprefix=machine+learning+sys%2Caps%2C174&sr=8-1)


## Industry Blogs:
- [[Meta] The AI behind unconnected content recommendations on Facebook and Instagram](https://ai.meta.com/blog/ai-unconnected-content-recommendations-facebook-instagram/)
- [[Pinterest] Related Pins at Pinterest:
The Evolution of a Real-World Recommender System](https://arxiv.org/pdf/1702.07969.pdf)
- [[Pinterest] Evolution of Ads Conversion Optimization Models at Pinterest](https://medium.com/pinterest-engineering/evolution-of-ads-conversion-optimization-models-at-pinterest-84b244043d51)
- [[Doordash] Personalizing the DoorDash Retail Store Page Experience](https://doordash.engineering/2023/12/12/personalizing-the-doordash-retail-store-page-experience/amp/)
- [[Doordash] How DoorDash Improves Holiday Predictions via Cascade ML Approach](https://doordash.engineering/2023/08/31/how-doordash-improves-holiday-predictions-via-cascade-ml-approach/)] [📝 notes](https://github.com/qizhong19920114/MLE_Resources/blob/main/notes/how-doordash-improves-holiday-predictions-via-cascade-ml-approach.txt)
- [[Doordash] Augmenting Fuzzy Matching with Human Review to Maximize Precision and Recall](https://doordash.engineering/2022/10/18/augmenting-fuzzy-matching-with-human-review-to-maximize-precision-and-recall/)
