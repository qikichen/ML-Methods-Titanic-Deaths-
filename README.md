# ML-Methods-Titanic-Deaths-

IN COLLABORATION WITH THOMAS HEI CHUN CHAN

Compares the accuracy of different ML Classification Methods.
Used several Machine Learning algorithms (from scikit) and Titanic Death data to predict whether a person of that age, gender, fare price etc. would have survived the Titanic. Data has been downloaded from a GitHub repository. The code required the cleaning of data (NaN removal and Labeling) as well as training and testing. The models have been saved as joblib files and the decision tree has been saved as a schematic .dot file.

Models:
Decision Tree
Cross Validated Decision Tree
SVM
Naive Bayes - Gaussian
Naive Bayes - Multinomial
Naive Bayes - Binomial

Using training data (25% Testing Data), this is the ranking of accuracy as calculated:

1. Decision Tree Cross Validated: 0.8001 ± 0.0259
2. BernoulliNB: 0.7806 ± 0.0267
3. GaussianNB: 0.7765 ±0.0240
4. Decision Tree Base: 0.7619 ± 0.0289
5. MultinomialNB: 0.6936 ± 0.0301
6. SVM: 0.6695 ± 0.0303
