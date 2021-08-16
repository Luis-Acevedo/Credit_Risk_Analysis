# Credit_Risk_Analysis

## New Tools 

Our team has been hired to test credit card data for bias and apply new machine learning modules. The company believes that a newer machine learning model could allow for better opportunities for it's customers. Using the same dataset we will be taking 6 different machine learning modules and comparing them. We will look and see if the two new machine learning modules have any significant changes. 

## Machine Learning Model Tests

- ![Naive](https://github.com/Luis-Acevedo/Credit_Risk_Analysis/blob/main/Challenge/Photos/Naive.png)

  - RandomOverSampler Results

    * Balanced Accuracy: 62.87%

    * High Risk Results:
      
      * Precision: .01

      * Recall: .62

    * Low Risk Results:

      * Precision: 1.00

      * Recall: .64

- ![Smote]("https://github.com/Luis-Acevedo/Credit_Risk_Analysis/blob/main/Challenge/Photos/Smote.png")

  - SMOTE Results

    * Balanced Accuracy: 61.45%

    * High Risk Results:
      
      * Precision: .01

      * Recall: .56

    * Low Risk Results:

      * Precision: 1.00

      * Recall: .67

- ![Undersampling]("https://github.com/Luis-Acevedo/Credit_Risk_Analysis/blob/main/Challenge/Photos/Undersampling.png")

  - ClusterCentroids Results

    * Balanced Accuracy: 61.45%

    * High Risk Results:
      
      * Precision: .01

      * Recall: .56

    * Low Risk Results:

      * Precision: 1.00

      * Recall: .46

- ![Combo]("https://github.com/Luis-Acevedo/Credit_Risk_Analysis/blob/main/Challenge/Photos/Combo.png")

  - SMOTEENN Results

    * Balanced Accuracy: 51.33%

    * High Risk Results:
      
      * Precision: .01

      * Recall: .72

    * Low Risk Results:

      * Precision: 1.00

      * Recall: .56

- ![Bal_ran_for]("https://github.com/Luis-Acevedo/Credit_Risk_Analysis/blob/main/Challenge/Photos/bal_ran_for.png")

  - BalancedRandomForestClassifier Results

    * Balanced Accuracy: 78.23%

    * High Risk Results:
      
      * Precision: .04

      * Recall: .66

    * Low Risk Results:

      * Precision: 1.00

      * Recall: .91

- ![Ensemble]("https://github.com/Luis-Acevedo/Credit_Risk_Analysis/blob/main/Challenge/Photos/Ensemble.png")

  - EasyEnsembleClassifier Results

    * Balanced Accuracy: 91.09%

    * High Risk Results:
      
      * Precision: .08

      * Recall: .87

    * Low Risk Results:

      * Precision: 1.00

      * Recall: .95

## Recommendations

Based on our findings we can tell the company the newer models are more accurate. These newer machine learning models are built to eliminate more bias than older models. As the world keeps changing it is always important to compare our current technology with newer technology. In this case we can recommend the company move to the newer models with their improved accuracy and recall.