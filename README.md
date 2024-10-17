# Logistic-Regression-with-Under-Sampling---Credit-Card-Fraud-Detection

Dataset Source - https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

=> The goal is to detect fraudulent transactions using machine learning. The dataset contains over 284,000 transactions, with only 492 marked as fraudulent, resulting in a highly imbalanced distribution.

1. Data Exploration:
- Verified that the dataset has no missing values.
- Analyzed class distribution: 99.8% of transactions are legitimate, while only 0.2% are fraudulent.

2.Data Preprocessing & Sampling:
- Separated legitimate and fraudulent transactions.
- Performed undersampling by selecting an equal number of legitimate transactions (492) to match the number of fraudulent transactions, thus balancing the dataset.
- Created a balanced dataset for analysis.

3. Modeling:
- Employed Logistic Regression to classify transactions.
- Split the balanced dataset into training and testing sets, with 80% for training and 20% for testing.
- Evaluated the model's performance using accuracy metrics.

=> Conclusion
- The project successfully developed a fraud detection model using a balanced dataset, addressing the significant class imbalance in the original data. By implementing logistic regression, the model effectively classified transactions, demonstrating the importance of proper sampling techniques in enhancing predictive performance. This approach can serve as a foundation for further refinements and more complex algorithms to improve accuracy and reduce false positives in fraud detection systems.

=> Contact Us

1. Email: uttamsojitra.ds@gmail.com

2. LinkedIn: https://www.linkedin.com/in/uttam-sojitra-6aa781236/
