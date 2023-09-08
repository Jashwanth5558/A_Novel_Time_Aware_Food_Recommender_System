# A_Novel_Time_Aware_Food_Recommender_System

ABSTRACT
The need for personalized meal recommendations has grown over the last few years as a result of 
the exponential rise of digital platforms and online food delivery services. Traditional 
recommender systems frequently disregard the temporal aspect of food intake and fail to take 
consumers' changing tastes over time into account. We suggest a unique time-aware meal 
recommender system that makes use of deep learning methods and graph clustering to overcome 
this constraint. Our method captures both user preferences and temporal patterns in food intake by 
combining the strength of deep learning with that of graph clustering. In order to extract rich 
features from user profiles, such as history food preferences, demographic data, and contextual 
information, we first use deep learning models. These models efficiently capture the nuanced 
interactions between consumers and food products, enabling accurate personalized 
recommendations.

PROPOSED SYSTEM
1) Ingredients-aware food recommender-system: Unlike traditional collaborative-based food recommender systems,
our model integrates both collaborative filtering-based model (user-based phase) and content-based model (foodbased phase). As a result, a set of foods that both suit the user's preferences and utilize his/her previous ratings are
recommended.
2) Time-aware food recommender-system: A novel time-aware similarity measure that takes into account changes in
food preferences or diet over time is developed in this paper. This makes the proposal suitable to handle cases where
users change his/her rating / preferences over time.
3) Trust-aware food recommender-system: A trust-aware food recommender-system is developed to overcome the
cold start user and cold start foods problems of the traditional collaborative filtering-based food recommendersystems. Our proposed model builds a trust network of users based on trust (follower following)
statements to predict user ratings efficiently.
The trust network generation plays an important role in addressing the neighbor selection problem. Trust statements
can be used to predict the rating of unseen items
in food recommender-systems since there is a high correlation between users' trust and user ratings-based similarity
measure. The user's trust network and the user ratings-based similarity are integrated in this study to address the
data sparsity problem utilizing knowledge that is stored outside of the user's local neighborhood
of similarity.
4) Community-aware food recommender-system: Contrary to previous works where users' communities are not
considered in the food recommendation process, our model explicitly accounts for such aspects where the optimal
number of users' clusters is determined automatically. Moreover, using a graphical like representation
where edge weights are calculated according to user ratings-based similarity and trust network, the proposed
method accommodates sparse datasets.
PROPOSED SYSTEM ADVANTAGES
➢ The purpose Time-aware food recommender-system based on Deep and Learning and Graph Clustering
(TDLGC) and Machine Learning Classifiers.
➢ (1) User based rating prediction, and (2) Food-based rating prediction.
➢ In the first phase, (i) by utilizing both the user rating and the follower-following network, the user-user
similarity matrix as well as the users' trust network are generated.
➢ Then,(ii) based on the user similarities and the trust network, the given user set is mapped onto a
weighted graph.
➢ In the next step, (iii) a novel time-aware graph clustering algorithm is proposed to cluster the users into
different groups accordingly. Finally, (iv) utilizing users' clusters from previous step, user similarity and
historical ratings, new user-based ratings are predicted.

