### DTSC-610-Credit-Card-Fraud-Detection

Summary:
Overall, this project provided insights into the process of building a fraud detection system using machine learning, highlighting the importance of data preprocessing, feature engineering, model selection, and evaluation. 

In this project, we leveraged machine learning techniques to build a predictive model for identifying fraudulent credit card transactions. We began by exploring a synthesized credit card transaction dataset, examining variables' distributions and the balance between fraudulent and genuine transactions.

Feature engineering was crucial to enhance model performance. We normalized and scaled the features using StandardScaler from Scikit-Learn to ensure consistency in model training.

For model selection, we opted for algorithms suitable for classification tasks, such as Logistic Regression, SVM, and Random Forest. These algorithms were chosen for their ability to handle large datasets, nonlinear relationships, and interpretability.

The data was split into training and testing sets using train_test_split, and the models were trained on the training set and validated on the test set. Techniques like cross-validation were employed to ensure the model's robustness and generalizability.

Model evaluation was performed using various metrics including accuracy, precision, recall, F1 score, ROC, and AUC. Confusion matrices were created to interpret the results and understand the trade-offs between false positives and false negatives in the context of fraud detection.

Finally, the trained model was saved using joblib or pickle for persistence, allowing it to be loaded and used for predicting new data.
