Predicting Suicide Risk in Women with Postpartum Depression

Overview
This project aims to predict the risk of suicide in women experiencing postpartum depression using machine learning models. By utilizing techniques such as Decision Trees (DT) and Support Vector Machines (SVM), this project seeks to identify at-risk individuals through data analysis and preprocessing methods.


Dataset
The dataset utilized in this project from  kaggle:https://www.kaggle.com/datasets/parvezalmuqtadir2348/postpartum-depression
1503 records from a medical hospital using a questionnaire administered through a Google form.

Methodology/techniques
Exploratory Data Analysis (EDA): to understand data distribution and relationships.
Data Cleaning: Handling missing values.
One-Hot Encoding: to convert categorical variables into a numerical format
Model Training
Cross-validation

Models used
Decision Tree (DT): A model that uses a tree-like graph of decisions to predict outcomes.
Support Vector Machine (SVM): A classification method that finds the hyperplane that best separates different classes in the feature space.

Evaluation Metrics
Accuracy, Precision, Recall, and F1 Score, Confusion Matrix, the ROC curve (AUC)

Results
The Decision Tree (DT) model exhibited notable performance before and after hyperparameter tuning. Initially, the model achieved an average F1 score of 0.80 during 5-fold cross-validation, with a training accuracy of 0.94 and a testing AUC of 0.92. After hyperparameter tuning, the average F1 score improved to 0.88, reflecting better generalization across the folds. The training accuracy increased to 0.99, while the testing AUC rose to 94%, indicating enhanced model performance in distinguishing between classes in both training and testing phases. 

The SVM model demonstrated significant performance, achieving an average F1 score of 0.99 across all 5 folds. Additionally, both the training and testing AUC were at 1.0, indicating excellent capability in distinguishing between classes.