# Risky Business
 
![Credit Risk](Images/credit-risk.jpg)

# Model Analysis 

## 1. Credit Risk Ensemble 

## 1. Which model had the best balanced accuracy score?

    The EasyEnsembleClassifier had the best balanced accuracy score with 0.9254565671948463 compared to 
    BalancedRandomForest with 0.7871246640962729

## 2. Which model had the best recall score?

    The EasyEnsembleClassifier also had the best recall score with 0.94269108 compared to BalancedRandomForest with 0.90636443

## 3. Which model had the best geometric mean score?

    The EasyEnsembleClassifier had the best geometric score as well with 0.92529278 compared to BalancedRandomForest with 0.77785288

## 4. What are the top three features?

    The Top Three Feature Are:
    - 0.07376667607601396, total_rec_prncp 
    - 0.06390324452717588, total_rec_int 
    - 0.06073336071656837, total_pymnt_inv

## 2. Credit Risk Resampling 

## 1. Which model had the best balanced accuracy score?

   The Smote OverSampling and the Smoteenn CombinationSampling had a combined top score of 0.9946680739911509<br />
   
   - **The Other scores include:**<br />
   - Simple Logistic Regression 0.9892813049736127
   - Random  OverSampling 0.9946414201183431
   - ClusterCentroids UnderSampling 0.9932813049736127

## 2. Which model had the best recall score?

   The ClusterCentroids UnderSampling has the best recall score with 0.99447998<br />
   
   - **The Other scores include:**<br />
   - Simple Logistic Regression 0.99422204
   - Random  OverSampling 0.99411886
   - Smote OverSampling 0.99417045
   - Smoteenn CombinationSampling 0.99417045
    

## 3. Which model had the best geometric mean score?

   The Smote OverSampling and the Smoteenn CombinationSampling had a combined top score of 0.99466793 <br />
   
   - **The Other scores include:**<br />
   - Simple Logistic Regression 0.98926721
   - Random  OverSampling 0.99464126
   - ClusterCentroids UnderSampling 0.9932804821
