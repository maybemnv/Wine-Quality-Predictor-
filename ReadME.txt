Wine Quality Prediction Model
Project Overview
Welcome to the Wine Quality Prediction project! The objective of this endeavor was to create a predictive model that estimates the quality of wine based on various physicochemical properties. The insights gained from this project not only enhance our understanding of wine quality but also demonstrate the power of data-driven decision-making.
Dataset Information
* Number of Features: 13
* Number of Entries: 178
* Target Variable: A newly created quality column based on specific criteria related to the characteristics of the wine.
Data Preprocessing Steps
1. Data Loading: The dataset was imported from a CSV file.
2. Quality Column Creation: A quality column was derived using defined criteria, ensuring a structured approach to classification.
3. Missing Value Check: Thorough checks confirmed that there are no missing values in the dataset, contributing to data integrity.
4. Feature Scaling: Features were standardized using StandardScaler to ensure uniformity in data representation.
5. Data Splitting: The dataset was divided into training (80%) and testing (20%) sets to facilitate effective model training and evaluation.
Exploratory Data Analysis (EDA)
Exploratory data analysis was conducted to glean insights into the dataset:
* Descriptive Statistics: Summary statistics were generated to understand the dataset's structure and feature distributions.
* Visualizations: A range of visualizations, including histograms and box plots, were created to illustrate feature distributions.
* Correlation Analysis: A heatmap was utilized to explore correlations between features, revealing key relationships that inform the predictive model.
Modeling Techniques
A variety of modeling techniques were employed to identify the best-performing model, including:
* Logistic Regression
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* Decision Trees
* Random Forest (highlighted for exceptional performance)
* Gradient Boosting
* XGBoost
* LightGBM
* CatBoost
The Random Forest model achieved an impressive accuracy of 97.44%, underscoring its effectiveness in this context.
Model Evaluation
To validate model performance, cross-validation techniques were employed, ensuring robustness across different data splits. Additionally, feature importance analysis was conducted to understand which variables had the most significant impact on predictions.
Conclusion
This project has successfully demonstrated the potential of predictive modeling in assessing wine quality. The high accuracy achieved indicates a reliable model that can be further refined and potentially deployed for practical applications.
Getting Started
To replicate this analysis, follow these steps:
1. Clone the repository.
2. Ensure all necessary libraries are installed (pandas, scikit-learn, lightgbm, matplotlib, seaborn).
3. Run the main script to load the dataset, preprocess the data, and train the models.
Thank you for exploring this project! If you have any questions or feedback, please feel free to reach out.

