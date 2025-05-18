Description,
Cybersecurity Threat analysis

Overview 
This dataset represents a crucial segment of network security monitoring - real-time analysis of network traffic data aimed at identifying potential cybersecurity threats. The data is composed of anonymized numerical features representing various network parameters, such as traffic volume, port numbers, and types of protocols used. The objective is to determine whether a particular network activity is benign or a potential security threat.

Content 
Due to the sensitive nature of network security data, the information in this dataset has been thoroughly anonymized. This level of anonymity means that traditional feature engineering approaches may be less applicable, presenting an interesting challenge in handling high-dimensional, imbalanced data.

The primary challenge in most cases is to to develop machine learning models that can effectively identify these rare threat events without being overwhelmed by the volume of non-threatening data . Performance should be evaluated using metrics like AUC, F1 Score, Matthews Correlation Coefficient (MCC), or  recall rate, with an emphasis on robust cross-validation techniques.

Approach This dataset offers an opportunity to test the use of models like decision trees and understand the train-test split on complex data.

You are allowed to use libraries like sklearn
Bonus - implement this from scratch.

Data.csv
