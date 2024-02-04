# Crop-Recommendation-System

1. Data Import and Exploration:
- Use the Pandas library to load a CSV file named containing information about crops.
- Check the dataset's shape, check for null values, looks for duplicates, and provides general information using `info()` and `describe()` methods.

2. Data Encoding:
- The 'label' column in the dataset, representing crop names, is encoded into numerical values using a dictionary.
- A new column 'label_num' is created, and the original 'label' column is dropped.

3. Train-Test Split and Scaling:
- The dataset is split into features (X) and labels (y).
- The features are then scaled using both MinMaxScaler and StandardScaler.

4. Training Models:
- Several machine learning models are imported and trained on the dataset.
- Models include Linear Discriminant Analysis, Logistic Regression, Naive Bayes, Support Vector Machine, K-Nearest Neighbors, Decision Tree, Random Forest, Bagging, AdaBoost, Gradient Boosting, and Extra Trees.
- Model accuracy is printed for each model on the test set.

5. Predictive System:
- A predictive function is defined to recommend the best crop based on input parameters (N, P, K, temperature, humidity, pH, rainfall).
- The RandomForestClassifier is chosen as the final model.
- A set of sample input values is provided, and the predicted crop is printed.

6. Conclusion:
- The RandomForestClassifier is chosen for its high accuracy in this context.
- The final part of the script demonstrates how the model can be used to recommend a crop based on specific environmental conditions.

Successfully built a machine learning model that can predict the appropriate fertilizer for a given set of crop, soil, and weather conditions.
