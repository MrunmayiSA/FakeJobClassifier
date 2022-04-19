# Fake Job Classifier

* Dataset : Employment Scam Aegean Dataset (http://emscad.samos.aegean.gr/)
* Performed exploratory data analysis to find the words used to make the jobs sound genuine and industries that attract scammers
* Processed text data (stopwords, punctuation removal) and one-hot-encoded it for ML
* Used Synthetic Minority Oversampling Technique to overcome class imbalance in the target (17,014 real and 866 fake job postings)
* Used Grid Search Cross Validation to find the best parameters for ML models (10 folds)
* Following classification algorithms were tested and compared:
  * Logistic(Ridge) regression
  * KNN (22 neighbours)
  * SVM (rbf kernel)
  * Random Forest (100 estimators)
  * MLP (relu activation function, adam solver)
* Both Random Forest and MLP gave best performance with an ROC-AUC score of 0.99


