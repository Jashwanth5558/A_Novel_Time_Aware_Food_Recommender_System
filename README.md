![image](https://github.com/Jashwanth5558/A_Novel_Time_Aware_Food_Recommender_System/assets/100793290/c0e5df0c-70cb-417d-b90c-6da8f3b49852)# A_Novel_Time_Aware_Food_Recommender_System

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
TEST CASE’S
1.User Preference Evolution: Test Case: Verify that the recommender system accurately captures the evolving 
preferences of a user over time. Steps: a. Simulate user interactions with food items over multiple time periods, 
ensuring changes in preferences. b. Evaluate the recommendations provided by the system at different time 
intervals. c. Compare the recommended items with the actual preferences of the user at each time period. Expected 
Result: The system should accurately capture the changing preferences of the user and provide relevant 
recommendations that align with the user's preferences at each time period.
2.Temporal Pattern Detection: Test Case: Validate that the system effectively identifies temporal patterns and trends 
in food consumption. Steps: a. Generate a dataset with food consumption patterns exhibiting different temporal 
trends (e.g., weekly, seasonal). b. Input the dataset into the system and analyze the resulting clusters of food items. 
c. Compare the identified clusters with the expected temporal patterns in the dataset. Expected Result: The system 
should successfully identify the temporal patterns in the food consumption dataset, forming clusters that align with 
the expected temporal trends.
3.Cold-Start Recommendations: Test Case: Assess the system's performance in providing recommendations for new 
users or food items. Steps: a. Introduce a new user or a previously unseen food item to the system. b. Evaluate the 
recommendations generated by the system for the new user or food item. c. Assess the relevance and quality of the 
recommendations based on user feedback or predefined criteria. Expected Result: The system should handle the 
cold-start problem effectively by providing relevant recommendations for new users or food items, demonstrating 
its ability to generalize and leverage available data.
4. Computational Efficiency: Test Case: Measure the computational efficiency of the recommender system. Steps: a. 
Measure the training time required for the deep learning models used in the system. b. Evaluate the time taken to 
generate recommendations for a given user or food item. c. Compare the system's computational performance 
against predefined benchmarks or performance targets. Expected Result: The recommender system should 
demonstrate reasonable training and recommendation generation times, ensuring it can handle large-scale datasets 
and provide timely recommendations.
5. Contextual Relevance: Test Case: Verify that the system incorporates contextual information effectively for 
recommendation generation. Steps: a. Provide inputs with varying contextual factors such as time of day, location, 
or user-specific contexts. b. Evaluate the recommendations generated by the system and assess their relevance to 
the given context. Expected Result: The system should utilize contextual information to provide recommendations 
that align with the specific context, ensuring personalized and relevant suggestions

screenshots of the project.

![Screenshot (3)](https://github.com/Jashwanth5558/A_Novel_Time_Aware_Food_Recommender_System/assets/100793290/4644e4fa-ed0f-4446-aab7-46f24bc42eaa)
![Screenshot (4)](https://github.com/Jashwanth5558/A_Novel_Time_Aware_Food_Recommender_System/assets/100793290/1f85c6aa-6c70-451c-9487-34bbf7eaba11)
![Screenshot (5)](https://github.com/Jashwanth5558/A_Novel_Time_Aware_Food_Recommender_System/assets/100793290/4933987e-dec7-46f8-b340-d9e5c5446e4f)
![Screenshot (6)](https://github.com/Jashwanth5558/A_Novel_Time_Aware_Food_Recommender_System/assets/100793290/7ee92755-9598-4f66-91fd-3c124ff44c9c)





