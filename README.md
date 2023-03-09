# Homogeneous-Ensemble-random-forest
Homogeneous ensemble random forest is a collection of classifiers of the same type, built upon a different subset of data as we use to do in the Random Forest model. The trees in homogeneous enesemble  are usually of the same type, such as Classification and Regression Trees (CART) or Random Forest Trees.
This operation was conducted on two datasets and shows how homogeneous ensemble random forest can be applied on a given data set.

python 3 libraries used include;
pandas
numpy
scikit-learn
matplotlib

The data from the datasets is loaded and is preprocessed to prepare it for building a model. It is split into two, training dataset and testing dataset. A RandomForestClassifier is trained on the training data and is evaluated on test dataset to check its performance.

The data is loaded and is prepared for creating a model, then the model and is trained and tested and a test is done to check its performance. Upon complition the churn dataset model had its results came out highand this meant a good ensemble was achieved while insurance dataset moadel had lower results
