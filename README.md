The Credit Card Fraud Detection project aims to develop a machine learning model capable of identifying fraudulent transactions with high accuracy. Given the increasing prevalence of online transactions, detecting fraud in real-time is crucial for financial institutions to prevent significant monetary losses and protect customer data.

Objectives:
Data Preprocessing: The project began with data preprocessing, which included handling missing values, scaling features, and addressing class imbalance issues. Techniques like undersampling, oversampling, and Synthetic Minority Over-sampling Technique (SMOTE) were explored to balance the dataset.

Model Selection: The focus was on evaluating different machine learning models, specifically Logistic Regression and Decision Tree Classifier, to compare their performance in detecting fraudulent transactions.

Evaluation Metrics: The models were assessed using precision, recall, f1-score, and accuracy. These metrics are crucial in evaluating how well the models can distinguish between legitimate and fraudulent transactions.

Key Activities:
Data Exploration: Initial analysis of the dataset to understand the distribution of fraudulent and non-fraudulent transactions and feature correlations.

Feature Engineering: Creating new features and selecting the most relevant ones to improve model performance.

Model Training and Evaluation: Multiple models were trained and tested on various datasets, including the original dataset, scaled dataset, undersampled dataset, oversampled dataset, and SMOTE dataset. The models were fine-tuned, and their performance was evaluated using the confusion matrix and classification report.

Model Optimization: Hyperparameter tuning was conducted to optimize model performance further, ensuring the best possible detection rates for fraudulent transactions.

Results:
Logistic Regression and Decision Tree Classifier: Both models were compared based on their precision, recall, and f1-score. The Decision Tree Classifier generally showed better performance in terms of recall, which is crucial for identifying fraudulent transactions.

Best Model: The XGBoost model, when applied to the oversampled dataset, achieved the highest accuracy and macro-average f1-score, demonstrating its effectiveness in handling class imbalance and detecting fraud.

Conclusion:
The project successfully developed a robust fraud detection system capable of accurately identifying fraudulent transactions. The use of different sampling techniques, coupled with advanced machine learning algorithms, significantly improved detection accuracy, making the model a valuable tool for financial institutions in their fight against credit card fraud.
