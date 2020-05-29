# Heart-Disease-Prediction-Model-Using-Majority-Voting-Ensembles

This project deals with the study of “Heart Disease Detection Scheme Using Machine Learning Techniques” based on the values of various test results done on an individual. The technique used for this project is the majority voting ensemble learning so as to rightly classify the individuals as having a heart disease or not having a heart disease.

Ensemble learning involves combining various classification algorithms into a single, more powerful and a much more accurate algorithm. The ensemble thus formed works on the concept of majority voting (hard voting), wherein a new data point is classified into a certain class or category based on the majority of votes it gets from all the algorithms in the respective ensemble.

Various classification models were implemented for this project along with the implementation of k-fold cross validation and hyper-parameter tuning so as to get better accuracies over the test data. The algorithms implemented were, “Logistic Regression (LR)”, “Naïve Bayes (NB)”, “Decision Tree (DT)”, “Random Forest (RF)”, “Support Vector Machines (SVM)”, “Xtreme Gradient Boosting Machine (XGBM)”, “Light Gradient Boosting Machine (LGBM)” and “K-Nearest Neighbors (KNN)”.

Each algorithm was individually implemented on the dataset and based on the accuracies of these algorithms, few of them were combined together to form ensembles giving much higher accuracies as compared to a single classification model. 
Ensemble 1 consisting of SVM and NB and Ensemble 2 consisting of LR, RF and XGB were formed, with an accuracy of 91.8% and 88.52% respectively.

Other parameters like “Sensitivity”, “Specificity”, “Positive Predictive Value (PPV)” and “Negative Predictive Value (NPV)” were also evaluated for every model.
