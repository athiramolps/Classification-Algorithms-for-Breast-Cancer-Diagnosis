# Classification-Algorithms-for-Breast-Cancer-Diagnosis


Breast cancer remains one of the most prevalent and fatal diseases globally, underscoring the need for accurate diagnosis to improve patient outcomes. This repository explores the application of machine learning techniques to enhance the accuracy and efficiency of breast cancer diagnosis. By leveraging advanced computational algorithms, we aim to analyze complex patterns within medical data, facilitating more precise classification of breast cancer cases as benign or malignant.

## Objective
Our goal is to contribute to medical research and healthcare by providing innovative solutions to improve diagnostic accuracy and patient care.

## Approach
In this study, we employ both supervised and unsupervised machine learning methods for breast cancer diagnosis:

### Supervised Learning
- **k-Nearest Neighbors (kNN)**: Utilizes labeled training data to classify data points based on the majority class of their nearest neighbors.
- **Support Vector Machine (SVM)**: Finds the optimal hyperplane to separate data points into different classes, capable of handling linear and non-linear classification tasks.
- **Support Vector Machine with Principal Component Analysis (PCA)**: Integrates PCA for dimensionality reduction, enhancing SVM's performance by reducing computational complexity.
- **Naive Bayes**: A probabilistic classifier based on Bayes' theorem, known for its simplicity and efficiency in training and prediction.
- **Random Forest**: An ensemble learning algorithm that builds multiple decision trees and combines their predictions, robust to overfitting and suitable for high-dimensional data.

### Unsupervised Learning
- **Principal Component Analysis (PCA)**: Aids in identifying underlying patterns and structures within the data, complementing supervised learning.

## Evaluation Metrics
To assess model performance, we utilize the following metrics:

- **Test Score (Accuracy)**: Measures the proportion of correct predictions on a separate dataset.
- **Confusion Matrix**: Provides insights into the model's performance by comparing predicted and actual classes.
- **F1 Score**: The harmonic mean of precision and recall, balancing both metrics to evaluate model performance, particularly useful in imbalanced datasets.

## Conclusion
By exploring and comparing these machine learning models and evaluation metrics, we aim to identify the most suitable approach for accurate and reliable breast cancer diagnosis. These insights are crucial for clinicians and researchers to understand the model's performance and identify areas for improvement, ultimately advancing breast cancer diagnosis and treatment.
