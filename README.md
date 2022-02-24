# xAI and Bank Marketing
Explainable Artificial Intelligence applied on models trained for prediction of whether a customer will subscribe to a bank term deposit or not.

# DATASET
[Bank Marketing](https://www.kaggle.com/henriqueyamahata/bank-marketing) dataset from Kaggle: 
  - _The data is related with direct marketing campaigns (phone calls) of a Portuguese banking institution. The classification goal is to predict if the client will subscribe a term deposit (variable y). The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed._
  - 41188 data points, 20 user features (detailed description can be found on Kaggle)
  - very imbalanced data: 
  
    ![image](https://user-images.githubusercontent.com/88715320/155523915-21954ce8-4040-4df6-881a-c2d75afc21ab.png)

# EVALUATION
Accuracy is not a good evaluation method for imbalanced datasets, which is why **precision** is used instead (under assumption that false positives would make worse impact than false negatives).

# MODELS
1. Logistic Regression
2. Decision Trees
3. Random Forest
4. Suport Vector Machine
5. XGBoost

GridSearch was used to determine best parameters!

# EXPLAINABLE AI
For analysis and interpretability of different models two xAI libaries were used:
1. [ELI5](https://eli5.readthedocs.io/en/latest/)
2. [SHAP](https://shap.readthedocs.io/en/latest/)



