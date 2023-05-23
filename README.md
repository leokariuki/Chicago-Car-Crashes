## Chicago-Car-Crashes
# Overview
The City of Chicago has a vested interest in the safety and well-being of its residents. By analyzing car crash data, the city can gain valuable insights into the factors that contribute to accidents within its jurisdiction. This information can assist city officials and policymakers in making informed decisions regarding traffic infrastructure, road design, traffic regulations, and enforcement strategies. Understanding the prevalent causes of accidents can guide the city in implementing targeted measures to reduce accidents, improve traffic flow, and enhance overall road safety. Additionally, the analysis may reveal patterns or correlations between accidents and specific locations, weather conditions, or other variables, allowing the city to focus resources on areas that require attention and intervention.

# Business and Data Understanding
Business Understanding:
The project focuses on addressing the concerns of the Vehicle Safety Board and the City of Chicago regarding road safety and reducing traffic accidents. By analyzing the extensive car crash dataset, we aim to provide insights and recommendations that will contribute to the overall objective of creating safer roadways and minimizing the impact of accidents on the community. Understanding the causes, patterns, and contributing factors of car crashes will enable stakeholders to make informed decisions and implement targeted interventions to enhance traffic safety measures and reduce the occurrence of accidents.

Data Understanding:
The dataset provides comprehensive information about car crashes in Chicago, including factors such as traffic control devices, weather conditions, road defects, and contributing causes. It also includes details about the crash types, trafficway types, and the conditions of vehicles involved. By exploring and analyzing this dataset, we can gain a deeper understanding of the characteristics and trends of car crashes in Chicago. This understanding will help us identify potential areas for improvement and develop data-driven strategies to address the underlying causes of accidents. Through careful examination of the data, we can uncover valuable insights that will serve as a foundation for our subsequent analysis and modeling efforts to drive meaningful change in road safety.

# Modeling
A Logistic Regression model was built as the baseline model. The logistic regression model yielded low accuracy and F1 score of 40.4% and 27.3% respectively, suggesting that the model's performance in predicting the primary contributory cause of car accidents is not satisfactory. This indicates that the current model may not be capturing the underlying patterns and relationships effectively.

Alternative models were therefore be built to improve the performance.
The second model was a Random Forest Classifier that slighltly increased the performance of the model to an accuracy of 45.7% and F1 score of 34.9%.

The final model was a classification model using Extreme Gradient Boosting with tuned hyperparameters. This model yielded better performance overally as shown:
Accuracy: 0.45832467262523385
F1 Score: 0.3630366615661475
Precision: 0.39000601668021057
Recall: 0.45832467262523385

# Conclusion and Recommendations
Situations where predictions made by the model would be useful:

Investigating Contributing Factors: The model predictions can assist stakeholders in understanding the contributing factors behind accidents. By examining the importance of various variables in the prediction, stakeholders can identify the primary causes or conditions leading to accidents. This knowledge can be used to develop specific strategies, such as improving road infrastructure, enhancing traffic control devices, or implementing educational campaigns to address those factors effectively.

Evaluating Policy Interventions: If the stakeholders implement new policies or interventions to improve road safety, the model can be used to assess the effectiveness of those measures. By comparing the predicted outcomes before and after implementing the changes, stakeholders can evaluate the impact of their interventions and make data-driven decisions for further improvements.

Situations where the model predictions would not be useful:

Real-Time Accident Prediction: The model's predictions are based on historical data and existing variables. It may not be suitable for real-time accident prediction or immediate response scenarios where data on certain variables may not be available or rapidly changing. For real-time accident prediction, stakeholders would require a different approach, such as real-time sensor data, traffic cameras, or predictive models specifically designed for immediate responses.

Individual Driver Behavior: The model focuses on broader patterns and factors contributing to accidents at a population level. It may not capture individual driver behavior or specific instances of reckless driving, distracted driving, or other driver-related factors. Stakeholders should consider other approaches, such as driver education programs, traffic law enforcement, or telematics-based solutions, to address individual driver behavior.
