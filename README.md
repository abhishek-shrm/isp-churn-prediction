# isp-churn-prediction
A machine learning classification project that helps an Internet Service Provider in keeping existing subscribers by predicting if an existing customer will churn or not.

I highly recommend you to check out the [slides](https://docs.google.com/presentation/d/16Yt__PLiebZ4-BJP5iBDCgrNTKYpUW4p9UDSTYiQvxc/edit?usp=sharing) for getting an overview of the project.

## Data Sources
  [Internet Service Provider Customer Churn Dataset](https://www.kaggle.com/mehmetsabrikunt/internet-service-churn) by [Mehmet Sabri Kunt](https://www.kaggle.com/mehmetsabrikunt) on Kaggle.

## Problem Type
  Binary Classification of predicting customer churn.

## Evaluation Metric
  ROC-AUC

## Comparative Analysis of Models
| Algorithm           | Mean AUC-ROC | Standard Deviation |
|---------------------|--------------|--------------------|
| Logistic Regression |    0.9624    |       0.0027       |
| K-Nearest Neighbors |    0.9748    |       0.0020       |
| Decision Tree       |    0.9751    |       0.0021       |
| Random Forest       |    0.9827    |       0.0015       |
| XGBoost             |    0.9840    |       0.0014       |

## Results produced by Final Model(XGBoost Classifier)
### Confusion Matrix
![image](https://user-images.githubusercontent.com/33491664/137183426-9a5162f7-aa2f-4006-8cfb-5662d6cb910f.png)
### ROC-AUC
  Train Set: 0.9979611536456878 \
  Test Set: 0.9842082218633272
### f1-Score
  Train Set: 97.95469985401037 \
  Test Set: 95.16816245127367
### Accuracy
  Train Set: 97.72774717774959 \
  Test Set: 94.67
  
## Tool, Libraries & Frameworks used
- Numpy
- Pandas
- Matplotlib
- Scikit-Learn
- Seaborn
- XGBoost
- Optuna
- DVC
- AWS
