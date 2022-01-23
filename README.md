# News-Recommendation-at-scale-using-Neo4j
MIcrosoft News Dataset (MIND) is a sample of 1 million anonymized users and their click behaviors collected from the Microsoft News website. It includes about 15M impressions logs for about 160K English News articles to quickly predict similar news based on user preferences and enable rank-ordered recommendation queries personalized to each user by leveraging Collaborative Filtering and KNN.


## Dependencies

1. Need Neo4j Desktop 1.4.12 installed with PC. (16GB of Ram is required by Neo4j to do in-memory graph computations)
2. Add APOC and Graph Data Science Plugins while creating DBMS in Neo4j Desktop.
3. Need Python 3.5.x or more.
4. pip install neo4j (make sure you uninstall neo4j library if already exists in your site-packages in python and re-install it).


### Make sure to close the driver at the end of the session.
