 # Data_mining+Cluster_analysis(bert)
 ## 简介
 这是项目可以实现对于专利文本的向量化，进而对专利文本进行聚类，并基于聚类的结果对于专利文本进行时序分析。
 
 文本向量化我们用到了Bert模型，聚类过程我们用到了Kmeans模型。
 
 ## 特色
 我们解决了几个有趣的问题：
 
 1.我们发现句子长短差异对最终的聚类结果会产生影响，聚类倾向于将长短句进行分离，而文本的这个特征我们希望是被忽略的，为了解决这个问题在2.1中我们实现了长句分割。
 
 2.在2.2中，我们加入了停词机制，可以通过停词表对专利文本进行停词。
