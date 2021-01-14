# Ensemble-Model
Gender Classification of twitter users using Ensemble Modeling
Building three Machine Learning Models.Compare the accuracy of all three and finding out the best model.

Dataset:
Name: Information.csv
Description: The above dataset contains the information of
about different tweets. It consists about the tweet account
unit_id, when was the profile created, description of the
profile, names of the profiles, the tweets made by these
profiles, their locations, time zones etc.


NLP tools are used to extract user information and sentiment anaysis

Classification Algorithms chosen:
1. KNN (K Nearest Neighbors)
2. SVM (Support Vector Machine)
3. Random Forest
4. Naïve Bayes
EDA and Data Visualization:
● First, we checked for null values in the given dataset.
● There were many null values in different columns.
● Next, replaced the null values with ‘0’ value and then
removed the columns that are totally ‘0’.
● Lastly, we checked for columns that could be dropped from the dataset, the columns:‘tweet_coord’,’tweet_location’,’user_timezone’ were dropped.


● For the Data Visualization, we have plotted all different columns in various types of graphs plots to get a clear
visual representation of our dataset.
Assigning variables to Train/Test:
● After Data Visualization, we have done Label
Encoding by importing it from SKLearn library
to fit_transform two columns.
● Dependent Variable: - Gender
● Independent Variable: - Remaining columns


ML Algorithms:
1.KNN: -
● For this model, we imported KNN model from
SKlearn library. Then we imported KNeighborClassifier from sklearn.neighbors as knn,then we fitted the train data in knn.

2. SVM: -
● For this model, we simply imported the concerned module from Sklearn library as ‘svc’ and passed our dataset.
● Data is fitted into svc as svc.fit() to calculate the accuracy.

3. Random Forest: -
● For this model, we again imported the concerned module from SKlearn library as ‘rfc’.
● Data is fitted into rfc as rfc.fit() to calculate the accuracy.

4. Naïve Bayes: -
● For this model, we imported Naïve Bayes model from SKlearn library as sklearn.naive_bayes, then we fitted the train data as nb.fit().


● Then the accuracy has been calculated.
Accuracies: -

Accuracy of KNN algo is: - 0.4618490109002826
Accuracy of SVM algo is: - 0.38070246265643926
Accuracy of random_forest algo is: - 0.5163504238998788
Accuracy of Naive_bayes algo is: - 0.6685506661283811
So the best algorithm for this classification is Naïve_bayes algorithm since it has the best accuracy score
