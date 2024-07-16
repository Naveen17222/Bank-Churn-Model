# Bank Customer Churn Model
Explanation about the project

In this project we have used SVM(Support Vector Machine) to classify the bank customers into the customers who are likely to leave the bank(close their account) using the dataset available corresponding to it.

We have analysed the data and have performed required data encoding, performed proper data preprocessing and also have handled the data imbalance for the corresponding class by using the techniques like Random Under Sampling and Random Over Sampling.

Three different datasets were created:

Original dataset

Random under-sampled dataset

Random over-sampled dataset

A Support Vector Machine (SVM) classifier was then trained on each of these datasets, and the accuracy of each model was evaluated using confusion matrices and classification reports.

We also compared the accuracy of the SVM model by using actual data, random oversampled data and random undersampled data which came to be similar.

Finally we perfomed hyperparameter tuning for improving the model and then performed the same for all the three cases of dataset and found by analysing the results that the accuracy of SVM model after hyperparameter tuning which was trained using random oversampled data was maximum.

Hence, we concluded that the model trained with random oversampled data and after hyperparameter tuning is most accurate and practical to be used for the task.
