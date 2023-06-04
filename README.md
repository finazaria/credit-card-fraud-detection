# 🔍 Credit Card Fraud Detection: Handling Imbalanced Data and Optimizing Classification Models

Welcome to the GitHub repository for an insightful data analytics project that focuses on effectively handling imbalanced datasets and identifying the best classification algorithm for predicting fraud and non-fraud cases in the renowned [Kaggle Credit Card Fraud Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

### 📊 Imbalanced Data Challenges:
In this project, we tackle the inherent challenges posed by imbalanced datasets. Through careful analysis and implementation of various techniques, we address the issue of class imbalance to ensure accurate modeling and mitigate biased predictions.

### 💡 Fraud Detection Analysis:
With a primary objective of fraud detection, we meticulously analyze the Credit Card Fraud Dataset. Leveraging cutting-edge data analytics techniques, we compare and evaluate multiple classification algorithms to determine the optimal model for accurate fraud identification.

### 🧠 Neural Network Implementation:
As part of this project, we delve into the realm of neural networks. We implement a simple yet powerful Neural Network model specifically designed for predicting fraud and non-fraud cases. By fine-tuning its architecture and optimizing hyperparameters, we aim to achieve superior performance in detecting fraudulent activities.

&nbsp;

## Project Highlights:

* Comprehensive analysis of the Kaggle Credit Card Fraud Dataset.
* Application of techniques to address class imbalance and enhance model performance.
* Evaluation and comparison of various classification algorithms for fraud detection.
* Implementation and optimization of a Neural Network model for accurate fraud prediction.

&nbsp;

## Conclusion
* Overall, the model which was trained by the oversampled dataset (SMOTE) results in a higher accuracy prediction than the model which was trained by the undersampled dataset. Amongst the classifier algorithm, LogisticRegression has the highest accuracy to predict the fraud and non-fraud cases.
* However, one thing to note is that, we removed the outliers from the undersampled dataset, but we did not remove the outliers from the oversampled dataset. This may have affect the accuracy and prediction score result. So, we have to note that in our next exploration, we will try to calculate the accuracy and prediction score of a model that was trained by an oversampled dataset which has been cleared from outliers.
* In these kinds of financial cases, logacally, it is preferable to use oversampling instead of undersampling. Why? Because if we use undersampling, we cut off the Non-fraud cases. If we cut off the non-fraud cases, it will decrease the possibility of the case being detected as non-fraud. Hence, it will increase the chance of a non-fraud cases being classified as a fraud cases.
* In a real world case, it must be frustratingly confusing for a customer if their card suddenly got blocked because it was being classified as a fraud case. This kind of misclassification can increase the number of customer complaints and customer disatisfaction.
