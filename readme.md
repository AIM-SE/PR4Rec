# Survey Papers

<a href=Survey_papers.md>survey papers</a>

# Problems/Approaches

## Session based RecSys

### Based on Attention Model 

Pan, Zhiqiang, Fei Cai, Yanxiang Ling, and Maarten de Rijke. 2020. “Rethinking Item Importance in Session-Based Recommendation.” In SIGIR. http://arxiv.org/abs/2005.04456.

Chen, T., and R. C. Wong. 2019. “Session-Based Recommendation with Local Invariance.” In 2019 IEEE International Conference on Data Mining (ICDM), 994–99.

Wu, Shu, Mengqi Zhang, Xin Jiang, Xu Ke, and Liang Wang. 2019. “Personalizing Graph Neural Networks with Attention Mechanism for Session-Based Recommendation.” IEEE Transactions on Knowledge and Data Engineering 31 (9). http://arxiv.org/abs/1910.08887.

Xu, Chengfeng, Pengpeng Zhao, Yanchi Liu, Victor S. Sheng, Jiajie Xu, Fuzhen Zhuang, Junhua Fang, and Xiaofang Zhou. 2019. “Graph Contextualized Self-Attention Network for Session-Based Recommendation.” In Proc. 28th Int. Joint Conf. Artif. Intell.(IJCAI), 3940–46. pdfs.semanticscholar.org.

Zhang, S., Y. Tay, L. Yao, and A. Sun. 2018. “Next Item Recommendation with Self-Attention.” arXiv.” Information Retrieval.

Wang, Tian, and Kyunghyun Cho. 2017. “Attention-Based Mixture Density Recurrent Networks for History-Based Recommendation.” arXiv [cs.LG]. arXiv. http://arxiv.org/abs/1709.07545.

Li, Jing, Pengjie Ren, Zhumin Chen, Zhaochun Ren, Tao Lian, and Jun Ma. 2017. “Neural Attentive Session-Based Recommendation.” In Proceedings of the 2017 ACM on Conference on Information and Knowledge Management, 1419–28. CIKM ’17. New York, NY, USA: Association for Computing Machinery.

### Based on Neural Language Model 

Zhang, Yuanxing, Pengyu Zhao, Yushuo Guan, Lin Chen, Kaigui Bian, Lingyang Song, Bin Cui, and Xiaoming Li. 2020. “Preference-Aware Mask for Session-Based Recommendation with Bidirectional Transformer.” ICASSP 2020 - 2020 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP). doi:10.1109/icassp40776.2020.9054639.

- Approach : based on Transformers with mask considering user's preference
- Dataset : LastFM, ML-20m, ML-YOOCHOOSE
- github : 

Sun, Fei, Jun Liu, Jian Wu, Changhua Pei, Xiao Lin, Wenwu Ou, and Peng Jiang. 2019. <b>“BERT4Rec: Sequential Recommendation with Bidirectional Encoder Representations from Transformer.”</b> In Proceedings of the 28th ACM International Conference on Information and Knowledge Management, 1441–50. CIKM ’19. New York, NY, USA: Association for Computing Machinery.

- Approach : based on BERT
- Dataset : Beauty, Steam ML-1m, ML-20m
- github : https://github.com/FeiSun/BERT4Rec 

Anh, Pham Hoang, Ngo Xuan Bach, and Tu Minh Phuong. 2019. <b>“Session-Based Recommendation with Self-Attention.”</b> In Proceedings of the Tenth International Symposium on Information and Communication Technology, 1–8. SoICT 2019. New York, NY, USA: Association for Computing Machinery.

- Approach : based on dual Transformers
- Dataset : Beauty, Steam ML-1m, ML-20m
- github : 

Kang, Wang-Cheng, and Julian McAuley. 2018. <b>“Self-Attentive Sequential Recommendation.”</b> In IEEE International Conference on Data Mining. http://arxiv.org/abs/1808.09781.

- Approach : based on Transformer
- Dataset : Amazon Beauty, Amazon Games, Steam, MovieLens-1M
- github : https://github.com/kang205/SASRec

## Heterogenous RecSys

### Implementaions

- Heterogeneous Information Network Embedding: Methods and Implements : https://github.com/zhoushengisnoob/HINE

- PyTorch geometric : https://github.com/rusty1s/pytorch_geometric
- dgl(PyTorch, MXNet, TensorFlow) : https://github.com/dmlc/dgl
- stellagraph : https://github.com/stellargraph/stellargraph


### ETC

Zhao, Pengyu, Kecheng Xiao, Yuanxing Zhang, Kaigui Bian, and Wei Yan. 2020. “AMER: Automatic Behavior Modeling and Interaction Exploration in Recommender System.” arXiv [cs.LG]. arXiv. http://arxiv.org/abs/2006.05933.

- They argued that their model outperforms BERT4Rec

# DataSets

## List of Datasets

- https://github.com/daicoolb/RecommenderSystem-DataSet
- https://cseweb.ucsd.edu/~jmcauley/datasets.html
- https://github.com/caserec/Datasets-for-Recommender-Systems

### YOOCHOOSE (Recsys 2015)

- http://2015.recsyschallenge.com/challenge.html
- https://www.kaggle.com/chadgostopp/recsys-challenge-2015?select=dataset-README.txt

###  Digitica (CKIM 2016)

- http://cikm2016.cs.iupui.edu/cikm-cup
- https://competitions.codalab.org/competitions/11161#learn_the_details-data2

### Taobao/Tmall (IJCAI16)

- User Behavior Data on Taobao/Tmall IJCAI16 Contest
- https://tianchi.aliyun.com/dataset/dataDetail?dataId=53
- https://tianchi.aliyun.com/dataset/dataDetail?dataId=649

### Amazon Beautry 

- http://jmcauley.ucsd.edu/data/amazon/

### Steam

- https://cseweb.ucsd.edu/~jmcauley/datasets.html#steam_data

### Movie Lens

- 1M : https://grouplens.org/datasets/movielens/1m/
- 20M : https://grouplens.org/datasets/movielens/20m/


# Baseline Codes

##  AttRec, Caser, GRU4Rec, FPMC, TransRec, SASRec

- (Tensorflow 1.1+) https://github.com/slientGe/Sequential_Recommendation_Tensorflow

## NCF

- (Keras) https://github.com/hexiangnan/neural_collaborative_filtering

## Caser

- (pytorch) https://github.com/graytowne/caser_pytorch


# Wanna more papres?

## Must-read papers on Recommender System

- https://github.com/hongleizhang/RSPapers


### WWW

- (2019) https://www2019.thewebconf.org/accepted-papers

### SIGIR

- (2019) https://sigir.org/sigir2019/program/accepted/
- (2020) https://github.com/jihoo-kim/RecSys-Papers-from-SIGIR-2020

### WSDM

- (2019) http://www.wsdm-conference.org/2019/accepted-papers.php

### ICDM

- (2019) http://icdm2019.bigke.org/index.php/list-of-accepted-papers/

### ICIKM

- 

### RecSys 

- (2019) https://recsys.acm.org/recsys19/accepted-contributions/
- (2018) https://recsys.acm.org/recsys18/accepted-contributions/
- (2017) https://recsys.acm.org/recsys17/accepted-contributions/
- RecSys Best Papper : https://recsys.acm.org/best-papers/

## links to conference publications in graph-based deep learning

- https://github.com/naganandy/graph-based-deep-learning-literature
