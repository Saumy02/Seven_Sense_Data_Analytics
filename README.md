Project which i have Completed in Seventh Sense by NASSCOM are as follow:

**Breast_Cancer**

**College**

**Diabetes**

**Movies_Seventh_Sense**

**Pulsar_by_SS**

**Salary_Project**

**USA_Housing_by_Seventh_Sense**


**Key Steps and Methodologies**

1.Data Analysis and Preprocessing Imported necessary libraries: Pandas, NumPy, Matplotlib, Seaborn Loaded the dataset from a public URL Performed exploratory data analysis (EDA) using df.head(), df.info(), and value_counts() Removed duplicate values and set CustomerId as the index Applied encoding on categorical columns like Geography and Gender Created a new feature Zero Balance to indicate customers with zero balance

2.Handling Class Imbalance Visualized the class imbalance in the Churn target column Applied two sampling techniques to handle imbalance: Random Under Sampling (RUS) Random Over Sampling (ROS)

3.Data Splitting and Standardization Split the data into training and testing sets using train_test_split Standardized continuous features such as CreditScore, Age, Tenure, Balance, and Estimate3d Salary using StandardScaler

4.Model Building: Support Vector Machine (SVM) Built an SVM model using the SVC class from sklearn Evaluated the initial model performance using confusion_matrix and classification_report Improved the model using GridSearchCV for hyperparameter tuning Tuned parameters such as C, gamma, kernel, and class_weight Built and evaluated models with: Original Data Random Under Sampled Data Random Over Sampled Data

5.Model Evaluation and Comparison Compared model performances using: Confusion Matrix Classification Report (Precision, Recall, F1-score) Compared the following models: SVM with Original Data SVM with Random Under Sampling SVM with Random Over Sampling Key Libraries Used Pandas NumPy Matplotlib Seaborn Scikit-learn Imbalanced-learn (for RUS and ROS) Project Outcome The project successfully built and evaluated various SVM models to predict customer churn. The hyperparameter-tuned models using Random Over Sampling (ROS) showed the best performance, reducing class imbalance and improving prediction accuracy.

**How to Run the Code** 

Clone the repository Install required libraries using pip install -r requirements.txt Run the Jupyter notebook or Python script to reproduce the results Dataset The dataset is sourced from the YBI Foundation.
