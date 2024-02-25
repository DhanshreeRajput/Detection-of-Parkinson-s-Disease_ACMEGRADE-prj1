# Detection-of-Parkinson-s-Disease_ACMEGRADE-prj1

Summary :

Building and evaluating a Gradient Boosting Classifier model for predicting Parkinson's disease based on some features provided in the dataset. Here's a summary of what's happening in the code:

    Data Exploration: Initially, the code visualizes the distribution of numeric features using Seaborn's histplot function. This helps in understanding the skewness and distribution of each numeric feature.

    Correlation Analysis: Next, the code calculates the correlation matrix among the features and visualizes it as a heatmap using Seaborn's heatmap function. This helps in identifying correlations between different features, which can provide insights into potential relationships within the data.

    Data Preprocessing: The 'name' column is dropped from the dataset, assuming it's not contributing to the predictive task. Then, the dataset is split into features (X) and the target variable (Y).

    Model Training and Evaluation: The dataset is split into training and testing sets using the train_test_split function from scikit-learn. A Gradient Boosting Classifier model is trained on the training data and evaluated on both the training and testing sets.

    Evaluation Metrics: Various evaluation metrics such as accuracy, confusion matrix, recall, classification report, and Cohen's Kappa score are calculated and printed to assess the performance of the model on both the training and testing sets.

    Pickling: Finally, there's a mention of creating a pickle file, presumably to save the trained model for future use without having to retrain it every time.

Parkinson's Disease: Parkinson's disease is a neurodegenerative disorder that primarily affects movement. It is characterized by symptoms such as tremors, stiffness, slow movements, and impaired balance. Early diagnosis and treatment can help manage symptoms and improve the quality of life for individuals with Parkinson's disease. Machine learning models like the one built in this code can potentially assist in diagnosing Parkinson's disease based on relevant features extracted from patient data.
