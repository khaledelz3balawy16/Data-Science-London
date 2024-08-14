# Data-Science-London
Hello, I’m Khaled Ashraf, a Machine Learning Engineer
In this project, I focused on comparing different data scaling techniques using the K-Nearest Neighbors (KNN) classification model. The main goal was to determine which scaling technique yields the best performance for the KNN model. Here’s an overview of the project:
Data Loading and Preparation:
I loaded the data from CSV files and checked the data to ensure it was loaded correctly.
The data was processed and prepared for use in machine learning models, including reshaping the target labels to the required format.
Application of Scaling Techniques:
Three different scaling methods were applied to the dataset:
StandardScaler: Standardizes features by removing the mean and scaling to unit variance.
MinMaxScaler: Scales features to a specific range, usually between 0 and 1.
Normalizer: Scales individual samples to unit norm.
Model Training and Evaluation:
The KNN model was trained on the scaled datasets using each scaling technique, and performance was evaluated based on accuracy.
Results were visualized in a bar plot to compare the accuracy of the KNN model with each scaling technique to identify the best one.
Model Comparison:
After identifying the best scaling technique, I evaluated several classification models (KNN, SVM, RandomForest, and Logistic Regression) using the best scaler.
Grid Search with Cross-Validation was used to find the optimal hyperparameters for each model.
Final Predictions and Submission:
The best model (SVM with RBF kernel) was used to predict labels for the test dataset.
Results were saved to a CSV file for further analysis or submission
