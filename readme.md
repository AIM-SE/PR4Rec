# Survey Papers

<a href=Survey_papers.md>survey papers</a>

# New

* [[Selected papers in KDD2020]](kdd_20.md)

# Problems/Approaches

## Session based RecSys

### Based on Attention Model 

* Pan, Zhiqiang, Fei Cai, Yanxiang Ling, and Maarten de Rijke. 2020. “Rethinking Item Importance in Session-Based Recommendation.” In SIGIR. [[Link]](http://arxiv.org/abs/2005.04456)

* Chen, T., and R. C. Wong. 2019. “Session-Based Recommendation with Local Invariance.” In 2019 IEEE International Conference on Data Mining (ICDM), 994–99.

* Wu, Shu, Mengqi Zhang, Xin Jiang, Xu Ke, and Liang Wang. 2019. “Personalizing Graph Neural Networks with Attention Mechanism for Session-Based Recommendation.” IEEE Transactions on Knowledge and Data Engineering 31 (9). [[Link]](http://arxiv.org/abs/1910.08887)

* Xu, Chengfeng, Pengpeng Zhao, Yanchi Liu, Victor S. Sheng, Jiajie Xu, Fuzhen Zhuang, Junhua Fang, and Xiaofang Zhou. 2019. “Graph Contextualized Self-Attention Network for Session-Based Recommendation.” In Proc. 28th Int. Joint Conf. Artif. Intell.(IJCAI), 3940–46. pdfs.semanticscholar.org.

* Zhang, S., Y. Tay, L. Yao, and A. Sun. 2018. “Next Item Recommendation with Self-Attention.” arXiv.” Information Retrieval.

* Wang, Tian, and Kyunghyun Cho. 2017. “Attention-Based Mixture Density Recurrent Networks for History-Based Recommendation.” arXiv [cs.LG]. arXiv. [[Link]](http://arxiv.org/abs/1709.07545)

* Li, Jing, Pengjie Ren, Zhumin Chen, Zhaochun Ren, Tao Lian, and Jun Ma. 2017. “Neural Attentive Session-Based Recommendation.” In Proceedings of the 2017 ACM on Conference on Information and Knowledge Management, 1419–28. CIKM ’17. New York, NY, USA: Association for Computing Machinery.

### Based on Neural Language Model 

Zhang, Yuanxing, Pengyu Zhao, Yushuo Guan, Lin Chen, Kaigui Bian, Lingyang Song, Bin Cui, and Xiaoming Li. 2020. “Preference-Aware Mask for Session-Based Recommendation with Bidirectional Transformer.” ICASSP 2020 - 2020 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP). doi:10.1109/icassp40776.2020.9054639.

- Approach : based on Transformers with mask considering user's preference
- Dataset : LastFM, ML-20m, ML-YOOCHOOSE
- github : 

Sun, Fei, Jun Liu, Jian Wu, Changhua Pei, Xiao Lin, Wenwu Ou, and Peng Jiang. 2019. <b>“BERT4Rec: Sequential Recommendation with Bidirectional Encoder Representations from Transformer.”</b> In Proceedings of the 28th ACM International Conference on Information and Knowledge Management, 1441–50. CIKM ’19. New York, NY, USA: Association for Computing Machinery.

- Approach : based on BERT
- Dataset : Beauty, Steam ML-1m, ML-20m
- [[CODE]](https://github.com/FeiSun/BERT4Rec) 

Anh, Pham Hoang, Ngo Xuan Bach, and Tu Minh Phuong. 2019. <b>“Session-Based Recommendation with Self-Attention.”</b> In Proceedings of the Tenth International Symposium on Information and Communication Technology, 1–8. SoICT 2019. New York, NY, USA: Association for Computing Machinery.

- Approach : based on dual Transformers
- Dataset : Beauty, Steam ML-1m, ML-20m
- github : 

Kang, Wang-Cheng, and Julian McAuley. 2018. <b>“Self-Attentive Sequential Recommendation.”</b> In IEEE International Conference on Data Mining. http://arxiv.org/abs/1808.09781.

- Approach : based on Transformer
- Dataset : Amazon Beauty, Amazon Games, Steam, MovieLens-1M
- [[CODE]](https://github.com/kang205/SASRec)

## Heterogenous RecSys

* MAGNN: Metapath Aggregated Graph Neural Network for Heterogeneous Graph Embedding. (WWW`20)  [[Link]](http://arxiv.org/abs/2002.01680)
* Heterogeneous Graph Neural Network. (KDD`19)  [[Link]](https://www.kdd.org/kdd2019/accepted-papers/view/hetgnn-heterogeneous-graph-neural-network)
* Tripartite Heterogeneous Graph Propagation for Large-Scale Social Recommendation. (RecSys`19)  [[Link]](http://arxiv.org/abs/1908.02569)
* Learning Disentangled Representations for Recommendation. (NeurIPS`19) [[Link]](http://papers.nips.cc/paper/8808-learning-disentangled-representations-for-recommendation)
* Evolutionarily Learning Multi-Aspect Interactions and Influences from Network Structure and Node Content.” (AAAI`19) [[Link]](https://www.aaai.org/ojs/index.php/AAAI/article/view/3835)
* Heterogeneous Information Network Embedding for Recommendation.” (TKDE`19) [[LINK]](https://arxiv.org/pdf/1711.10730.pdf)

### Implementaions

- Heterogeneous Information Network Embedding: Methods and Implements : [[LINK]](https://github.com/zhoushengisnoob/HINE)

- PyTorch geometric : [[LINK]](https://github.com/rusty1s/pytorch_geometric)
- dgl(PyTorch, MXNet, TensorFlow) : [[LINK]](https://github.com/dmlc/dgl)
- stellagraph : [[LINK]](https://github.com/stellargraph/stellargraph)


### ETC

* Zhao, Pengyu, Kecheng Xiao, Yuanxing Zhang, Kaigui Bian, and Wei Yan. 2020. “AMER: Automatic Behavior Modeling and Interaction Exploration in Recommender System.” arXiv [cs.LG]. arXiv.  [[Link]](http://arxiv.org/abs/2006.05933) (They argued that their model outperforms BERT4Rec)

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

* AttRec, Caser, GRU4Rec, FPMC, TransRec, SASRec [[CODE:Tensorflow 1.1+]](https://github.com/slientGe/Sequential_Recommendation_Tensorflow)
* NCF [[CODE:keras]](https://github.com/hexiangnan/neural_collaborative_filtering)
* Caser [[CODE:pytorch]](https://github.com/graytowne/caser_pytorch)


# Wanna more papres?

## Conferences

### KDD : [[2020]](https://www.kdd.org/kdd2020/accepted-papers) [[2019]](https://www.kdd.org/kdd2019/accepted-papers) [[2018]](https://www.kdd.org/kdd2018/accepted-papers)

### WWW : [[2020]](https://dl.acm.org/doi/proceedings/10.1145/3366423#heading1) [[2019]](https://www2019.thewebconf.org/accepted-papers) [[2018]](https://www2018.thewebconf.org/proceedings/)

### SIGIR : [[2020]](https://sigir.org/sigir2020/accepted-papers/) [[2019]](https://sigir.org/sigir2019/program/accepted/) [[2020]](https://github.com/jihoo-kim/RecSys-Papers-from-SIGIR-2020)

### WSDM : [[2020]](https://www.wsdm-conference.org/2020/accepted-papers.php) [[2019]](http://www.wsdm-conference.org/2019/accepted-papers.php) [[2018]](http://www.wsdm-conference.org/2018/accepted-papers.html)

### ICDM : [[17-20 Nov 2020]](http://icdm2020.bigke.org/) [[2019]](http://icdm2019.bigke.org/index.php/list-of-accepted-papers/) [[2018]](http://icdm2018.bigke.org/index.php/list-of-accepted-papers/)

### CIKM : [[19-23 October 2020]](https://www.cikm2020.org/) [[2019]](https://dblp.org/db/conf/cikm/cikm2019) [[2018]](https://dblp.org/db/conf/cikm/cikm2018)

### RecSys : [[2020]](https://recsys.acm.org/recsys20/accepted-contributions/) [[2019]](https://recsys.acm.org/recsys19/accepted-contributions/) [[2018]](https://recsys.acm.org/recsys18/accepted-contributions/) [[2017]](https://recsys.acm.org/recsys17/accepted-contributions/) 

### RecSys Best Papper : [[LINK]](https://recsys.acm.org/best-papers/)

### RecSys Challenge : 
* [[2020]](http://www.recsyschallenge.com/2020/) [[2019]](http://www.recsyschallenge.com/2019/) [[2018]](http://www.recsyschallenge.com/2018/) [[2017]](http://www.recsyschallenge.com/2017/) [[2016]](http://2016.recsyschallenge.com/)


## Etc.

### Must-read papers on Recommender System

- [[LINK]](https://github.com/hongleizhang/RSPapers)

### links to conference publications in graph-based deep learning

- [[LINK]](https://github.com/naganandy/graph-based-deep-learning-literature)
