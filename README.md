# News-Recommendation-at-scale-using-Neo4j
MIcrosoft News Dataset (MIND) [[1]](#1) is a sample of 1 million anonymized users and their click behaviors collected from the Microsoft News website. It includes about 15M impressions logs for about 160K English News articles to quickly predict similar news based on user preferences and enable rank-ordered recommendation queries personalized to each user by leveraging Collaborative Filtering and KNN.

You can download the MIND dataset from https://msnews.github.io/. Download the training and validation set of MIND Large dataset and store it in the same directory as the 2 notebooks.

1. Data_Preprocessing_and_Loading.ipynb notebook preprocess data and models it as a graph and loads it in Neo4j DBMS.
2. News_Recommendation_Engine.ipynb notebook profiles the graph, Scaled Collaborative Filtering (Item-based) using Neo4j GDS with FastRP embeddings and KNN.


## Dependencies

1. Need Neo4j Desktop 1.4.12 installed with PC. (16GB of Ram is required by Neo4j to do in-memory graph computations)
2. Add APOC and Graph Data Science Plugins while creating DBMS in Neo4j Desktop.
3. Need Python 3.5.x or more.
4. pip install neo4j (make sure you uninstall neo4j library if already exists in your site-packages in python and re-install it).

### Make sure to close the driver at the end of the session.

## Citations

<a id="1">[1]</a> Fangzhao Wu, Ying Qiao, Jiun-Hung Chen, Chuhan Wu, Tao Qi, Jianxun Lian, Danyang Liu, Xing Xie, Jianfeng Gao, Winnie Wu and Ming Zhou. MIND: A Large-scale Dataset for News Recommendation. ACL 2020.
