# H&M Kaggle

H&M ran a kaggle competition that has long since expired. This project aims at competing in a dead contest. This is an attempt to get familiar with the "state of the art" ("state of the science") techniques in recommender systems. 

While it is focussed on fashion, the competition resembles the problems faced in any retail industry where data is divided into consumer, products and transactions data. 

### Approach

The "state of the science" recommendor systems, with proven performance winning Kaggle competitions, generally involve a scalable retrieval method for generating N possible candidates, which are then ranked with a more refined ranking algorithm .  In general, the retrieval task is a mixture (ensemble) of different algorithms with .  As this is Tabular data,  in order to in recommender systems is generally accepted to be a two part approach. 

#### RETRIEVAL METHODS

- collab filtering - 
Matrix factorization
LightGCM 

Top N products for men and women
Top N per category for season

#### RANKING ALGORITHM

LightGBM, Catboost

Features 
Items
- color embedding
- seasonality of colors, categories, etc. 
- collab filtering embeddings
- price
- price percentile

Users 
- Age
- Price percentile affinity
- category affinity
- Gender

### Data Analysis and Exploration

Fashion data is highly seasonal, coats in the winter and bikinis in the summer



