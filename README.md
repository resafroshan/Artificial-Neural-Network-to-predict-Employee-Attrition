# Artificial-Neural-Network-to-predict-Employee-Attrition

How Artificial Neural Networks differs from other models in predicting and classifying?

My study focuses on the benefits of using an Artificial Neural Network (ANN) model to predict Employee attrition. Employee attrition is a big concern for businesses today, and anticipating employee turnover can assist businesses in identifying at-risk personnel and taking proactive actions to retain them. In this research, an ANN model was trained using a dataset comprising various employee parameters such as age, education, job satisfaction, Monthly Income, and so on to predict the likelihood of an employee quitting the organization.
The dataset was preprocessed to manage variables, and categorical variables were converted to numerical values by one-hot encoding. The values are also scaled between 0 and 1 using Sklearn's MinMaxScaler. The ANN model was trained using the Keras API using the Tensorflow library. The model was trained on the preprocessed dataset using binary cross entropy as the loss function and Adam optimizer.
To avoid the model being biased towards the dominant class in the sample, the dataset was balanced using SMOTE (Synthetic Minority Over-sampling TEchnique) .
The model's performance was assessed using multiple measures like accuracy, precision, recall, and F1 score. On the test set, the model had an accuracy of 87%, indicating its effectiveness in predicting employee attrition. To understand the benefit of using an ANN model for prediction, the classification report of the ANN model is compared to the classification reports of other models trained on the same dataset, such as Logistic Regression, Naive Bayes, KNN (K Nearest Neighbors) and SVM (Support Vector Machines).
Along with classification reports, the ROC-AUC (Area under the curve of Receiver Operating Characteristic) of the models are compared to evaluate the difference in performances.
The comparison shows that the ANN model has higher scores in terms of classification report and ROC-AUC.
Organizations can utilize the project's findings to identify at-risk individuals and take the required steps to retain them, lowering employee turnover and boosting organizational performance.
