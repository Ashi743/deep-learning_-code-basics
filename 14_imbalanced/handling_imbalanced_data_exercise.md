#### Exercise: Handling imbalanced data in machine learning

1. Use [this notebook](https://github.com/codebasics/deep-learning-keras-tf-tutorial/blob/main/13_imbalanced/handling_imbalanced_data.ipynb) but handle imbalanced data using simple logistic regression from skelarn library. The original notebook using neural network but you need to use sklearn logistic regression or any other classification model and improve the f1-score of minority class using,
    1. Undersampling
    1. Oversampling: duplicate copy
    1. OVersampling: SMOT
    1. Ensemble

    [Solution](https://github.com/codebasics/deep-learning-keras-tf-tutorial/blob/main/14_imbalanced/handling_imbalanced_data_exercise_solution_telecom_churn.ipynb)    
   
2. Take this dataset for bank customer churn prediction : https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling
    1. Build a deep learning model to predict churn rate at bank
    1. Once model is built, print classification report and analyze precision, recall and f1-score
    1. Improve f1 score in minority class using various techniques such as undersampling, oversampling, ensemble etc
    
    [Solution](https://github.com/codebasics/deep-learning-keras-tf-tutorial/blob/master/14_imbalanced/Handling%20Imbalanced%20Data%20In%20Customer%20Churn%20Using%20ANN/Bank%20Turnover%20Customer%20Churn%20Using%20ANN.ipynb)
   Thanks https://github.com/src-sohail for providing this solution.
   3. Exercise: Predicting Customer Satisfaction
   Use the Customer Satisfaction dataset from Kaggle. - https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction

      1. Build a classification model to predict customer satisfaction.
      2. Initially, use a logistic regression model from scikit-learn.
      3. Print the classification report and analyze precision, recall, and f1-score.
      4. Try to improve the f1-score for the minority class using techniques like undersampling, oversampling, or ensemble methods.

      5. [Solution] : https://www.kaggle.com/code/teejmahal20/classification-predicting-customer-satisfaction 
   
   Thanks https://kaggle/teejmahal20 for providing this solution.

     
