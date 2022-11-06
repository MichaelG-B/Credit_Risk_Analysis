# Credit_Risk_Analysis

### Overview of the loan prediction risk analysis:

## The purpose of this analysis is well defined (4 pt)

-  The purpose of this credit risk analysis was to use different sampling techniques to train and test different machine learning models on unbalanced classification problems, which in this case is credit risk. We used oversampling, undersampling and combinatorial sampling techniques on the data as well as comparing the the results of a Balanced Random Forest and Easy Ensemble Classifier to predict credit risk.

## Results:

There is a bulleted list that describes the balanced accuracy score and the precision and recall scores of all six machine learning models (15 pt)

# Naive Random Oversampling

![](https://github.com/MichaelG-B/Credit_Risk_Analysis/blob/main/Scores%20screenshots/Naive%20Random%20Oversampling.png)

  - Balanced accuracy: (.647) precision: (.99) recall: (.69)
  
# SMOTE Oversampling

![](https://github.com/MichaelG-B/Credit_Risk_Analysis/blob/main/Scores%20screenshots/SMOTE%20Oversampling.png)

 - Balanced accuracy: (.636) precision: (.99) recall: (.65)
 
# Undersampling

![](https://github.com/MichaelG-B/Credit_Risk_Analysis/blob/main/Scores%20screenshots/Undersampling.png)

 - Balanced accuracy: (.529) precision: (.99) recall: (.45)
 
# Combination (Over and Under) Sampling

![](https://github.com/MichaelG-B/Credit_Risk_Analysis/blob/main/Scores%20screenshots/Over%20and%20Under%20sampling.png)

 - Balanced accuracy: (.637) precision: (.99) recall: (.57)
 
# Balanced Random Forest Classifier

![](https://github.com/MichaelG-B/Credit_Risk_Analysis/blob/main/Scores%20screenshots/Balanced%20Random%20Forest.png)

 - Balanced accuracy: (.787) precision: (.99) recall: (.91)
 
# Easy Ensemble AdaBoost Classifier

![](https://github.com/MichaelG-B/Credit_Risk_Analysis/blob/main/Scores%20screenshots/Easy%20Ensemble.png)

 - Balanced accuracy: (.925) precision: (.99) recall: (.94)

Summary:

- In summary of the results of this analysis, in comparing all the models tested there appears to be a strong argument for utilizing a Easy Ensemble AdaBoost Classifier to predict credit risk as this model had the highest Balanced accuracy score (.787) highest precison score (.99) and highest recall score (.94). The worst model to perform was using the undersampling method which provided results back of a Balanced accuracy score of (.529) a precision score of (.99) and a recall score of (.45); all the other models did better than this model.

- I would recommend the use of a Easy Ensemble AdaBoost Classifier model to predict credit risk.
