# Sequential/Session Recommendation Paperlist 

This is some research works about Sequential/Session Recommendation. This task is defined as: given a sequence s = {i1, i2, ..., in}, we aim to predict the next item in+1 which will be clicked by the user.

Please cite our paper: 
- Muyang Ma, Pengjie Ren, Yujie Lin, Zhumin Chen, Jun Ma, de Rijke, Maarten (2019). $\pi$-Net: A Parallel Information-sharing Network for Shared-account Cross-domain Sequential Recommendations. SIGIR'19, Paris, France, July 21-25, 2019
- Exploring Mixed Information Flow for Cross-domain Sequential Recommendations.


## Survey
- A Survey on Session-based Recommender Systems [Arxiv 2019] [[__PDF__]](https://arxiv.org/abs/1902.04864)
- Sequence-aware Recommender Systems [CSUR 2018] [[__PDF__]](https://arxiv.org/pdf/1802.08452.pdf)[[_code_]](https://github.com/mquad/sars_tutorial)
- Deep Learning for Sequential Recommendation: Algorithms, Influential Factors, and Evaluations [Arxiv 2019] [[__PDF__]](https://arxiv.org/abs/1905.01997)
- Sequential Recommender Systems  Challenges,Progress and Prospects [IJCAI 2019] [[_PDF_]](https://www.ijcai.org/Proceedings/2019/0883.pdf)

## Dataset
- Amazon [[_link_]](http://jmcauley.ucsd.edu/data/amazon/)
- Yoochoose [[_link_]](https://2015.recsyschallenge.com/challenge.html)
- MovieLen-1M [[_link_]](https://grouplens.org/datasets/movielens/1m/)
- MovieLen-20M [[_link_]](https://grouplens.org/datasets/movielens/20m/)

## Traditional Methods(MC/MDP)

- Playlist prediction via metric embedding [SIGKDD 2012][[__PDF__]](http://www.cs.cornell.edu/~jlmo/kdd12.pdf)
- Fusing similarity models with markov chains for sparse sequential recommendation [ICDM 2016][[__PDF__]](https://cseweb.ucsd.edu/~jmcauley/pdfs/icdm16a.pdf)
- Factorizing personalized markov chains for next-basket recommendation [WWW 2010][[__PDF__]](http://ramb.ethz.ch/CDstore/www2010/www/p811.pdf)
- Using temporal data for making recommendations [UAI 2001][[__PDF__]](https://arxiv.org/ftp/arxiv/papers/1301/1301.2320.pdf)
- An MDP-based recommender system [IMLR 2005][[__PDF__]](https://www.jmlr.org/papers/volume6/shani05a/shani05a.pdf)
- Personalized next-song recommendation in online karaokes [RecSys 2013][[__PDF__]](https://dl.acm.org/doi/10.1145/2507157.2507215)
- Learning hierarchical representation model for nextbasket recommendation [SIGIR 2015][[__PDF__]](https://dl.acm.org/doi/10.1145/2766462.2767694)
- Effective next-items recommendation via personalized sequential pattern mining [DASFAA 2012][[__PDF__]](https://www.researchgate.net/publication/262275934_Effective_Next-Items_Recommendation_via_Personalized_Sequential_Pattern_Mining)

## Deep Learning Methods

- Session-based Recommendations with Recurrent Neural Networks [ICLR 2016] [[__PDF__]](https://arxiv.org/pdf/1511.06939) [[__code__]](https://github.com/hidasib/GRU4Rec)
- Personalizing Session-based Recommendations with Hierarchical Recurrent Neural Networks [RecSys 2017] [[__PDF__]](https://arxiv.org/pdf/1706.04148) [[__code__]](https://github.com/mquad/hgru4rec)
- Improved recurrent neural networks for session-based recommendations [RecSys 2016][[__PDF__]](https://arxiv.org/abs/1606.08117)
- Neural Attentive Session-based Recommendation [CIKM 2017] [[__PDF__]](https://arxiv.org/pdf/1711.04725) [[__code__]](https://github.com/lijingsdu/sessionRec_NARM)
- RepeatNet: A Repeat Aware Neural Recommendation Machine for Session-based Recommendation [AAAI 2019] [[__PDF__]](https://arxiv.org/abs/1812.02646) [[__code__]](https://github.com/PengjieRen/RepeatNet)
- π-Net: A Parallel Information-sharing Network for Shared-account Cross-domain Sequential Recommendations [SIGIR 2019] [[__PDF__]](https://dl.acm.org/doi/10.1145/3331184.3331200) [[__code__]](https://bitbucket.org/Catherine_Ma/sigir2019_muyang_recommendation/)
- Sequential User-based Recurrent Neural Network Recommendations [RecSys 2017][[__PDF__]](https://cseweb.ucsd.edu/classes/fa17/cse291-b/reading/p152-donkers.pdf)
- Sequential Recommendation with User Memory Networks [WSDM 2018] [[__PDF__]](https://dl.acm.org/doi/abs/10.1145/3159652.3159668)
- A Collaborative Session-based Recommendation Approach with Parallel Memory Modules [SIGIR 2019] [[__PDF__]](https://dl.acm.org/doi/abs/10.1145/3331184.3331210) [[__code__]](https://github.com/wmeirui/CSRM_SIGIR2019)
- Session-based Recommendation with Graph Neural Networks [AAAI 2019] [[__PDF__]](https://arxiv.org/pdf/1811.00855) [[__code__]](https://github.com/CRIPAC-DIG/SR-GNN)
- Feature-level Deeper Self-attention Network for Sequential Recommendation [IJCAI 2019][[__PDF__]](https://www.ijcai.org/Proceedings/2019/0600.pdf)
- BERT4Rec: Sequential Recommendation with Bidirectional Encoder Representations from Transformer [CIKM 2019] [[__PDF__]](https://arxiv.org/abs/1904.06690) [[__code__]](https://github.com/FeiSun/BERT4Rec)
- SASrec: Self-Attentive Sequential Recommendation [ICDM 2018][[__PDF__]](https://arxiv.org/abs/1808.09781)
- Parallel recurrent neural network architectures for feature-rich session-based recommendations [RecSys 2016][[__PDF__]](https://dl.acm.org/doi/10.1145/2959100.2959167)
- Context-aware sequential recommendation [ICDM 2016][[__PDF__]](https://arxiv.org/abs/1609.05787)
- Incorporating dwell time in session-based recommendations with recurrent Neural networks [RecSys 2017][[__PDF__]](http://ceur-ws.org/Vol-1922/paper11.pdf)
- Mention recommendation for multimodal microblog with cross-attention memory network [SIGIR 2018][[__PDF__]](https://dl.acm.org/doi/10.1145/3209978.3210026)
- A review-driven neural model for sequential recommendation [IJCAI 2019][[__PDF__]](https://arxiv.org/abs/1907.00590)
- Sentiment-guided sequential recommendation [SIGIR 2020][[__PDF__]](https://dl.acm.org/doi/pdf/10.1145/3397271.3401330)
- STAMP: Short-Term Attention/Memory Priority Model for Session-based Recommendation [KDD 2018] [[__PDF__]](https://dl.acm.org/ft_gateway.cfm?id=3219950&type=pdf) [[__code__]](https://github.com/uestcnlp/STAMP)
- Improving Sequential Recommendation with Knowledge-Enhanced Memory Networks [SIGIR 2018] [[__PDF__]](https://dl.acm.org/doi/abs/10.1145/3209978.3210017) [[__code__]](https://github.com/RUCDM/KSR) 
- Rethinking the Item Order in Session-based Recommendation with Graph Neural Networks [[__PDF__]](https://arxiv.org/abs/1911.11942)
- Streaming Session-based Recommendation [KDD 2019] [[__PDF__]](https://dl.acm.org/doi/abs/10.1145/3292500.3330839)
- Empirical Analysis of Session-Based Recommendation Algorithms [Arxiv 2019] [[__PDF__]](https://arxiv.org/pdf/1910.12781)
- $S^3$-Rec: Self-Supervised Learning for Sequential Recommendation with Mutual Information Maximization [CIKM 2020] [[__PDF__]](https://arxiv.org/abs/2008.07873) [[__code__]](https://github.com/aHuiWang/CIKM2020-S3Rec)
- SSE-PT: Sequential Recommendation Via Personalized Transformer [RecSys 2020] [[__PDF__]](https://dl.acm.org/doi/pdf/10.1145/3383313.3412258) [[__code__]](https://github.com/SSE-PT/SSE-PT)
- Sequential Recommendation with Self-Attentive Multi-Adversarial Network [SIGIR 2020] [[__PDF__]](https://arxiv.org/abs/2005.10602)
- KERL: A Knowledge-Guided Reinforcement Learning Model for Sequential Recommendation [SIGIR 2020] [[__PDF__]](https://github.com/fanyubupt/KERL) [[__code__]](https://github.com/fanyubupt/KERL)
- Next-item Recommendation with Sequential Hypergraphs [SIGIR 2020] [[__PDF__]](http://people.tamu.edu/~jwang713/pubs/HyperRec-sigir2020.pdf) [[__code__]](https://github.com/wangjlgz/HyperRec)
- Self-Supervised Reinforcement Learning for Recommender Systems [SIGIR 2020] [[__PDF__]](https://arxiv.org/abs/2006.05779)
- Future Data Helps Training: Modeling Future Contexts for Session-based Recommendation [WWW 2020] [[__PDF__]](https://arxiv.org/abs/1906.04473) [[__code__]](https://github.com/fajieyuan/grec)
