# Building a Recommendatino Engine for IBM Watson Articles

The motivation for this project was to build a recommendation engine for IBM Watsons blog website. The enginer would
recommend articles to users based on similar users and the content that the user enjoys.

## Methods Explored

In the notebook provided I have explored recommendation engines that use user information to recommend articles (Collaberative Filtering).
I have also looked at solving the cold start problem by recommending users the most popular articles (Rank-Based).
Finally I explored Singular Value Decomposition which uses latent features to make recommendations.

## File descriptions 

* Recommendations_with_IBM.ipynb: Jupyter notebook containing main implementation and analysis.
* data/user-item-interactions.csv: Csv file with user-item interactions.
* data/articles_community.csv: Csv file with indexed items.
