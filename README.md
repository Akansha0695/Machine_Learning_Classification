                                           Titanic - Classification - Machine Learning

The "Titanic Survival Prediction" project involves analyzing and predicting the survival of passengers on the Titanic based on various features. The dataset initially includes information such as passenger class, sex, age, fare, and embarkation port. The data preprocessing phase involves removing unnecessary columns, handling missing values in the age and embarked columns, and dropping the "Cabin" column due to a high percentage of missing data.

Exploratory Data Analysis (EDA) is performed to understand the distribution of data and visualize the survival counts using a countplot. The dataset is then prepared for machine learning by converting non-numeric columns like "Sex" and "Embarked" using LabelEncoder. The target variable, "Survived," is explored, showing that there are two classes: 0 (did not survive) and 1 (survived).

The machine learning model, Logistic Regression, is implemented to predict survival outcomes. The model achieves an accuracy score of approximately 77.24% on the test data. Overall, the project involves data cleaning, exploration, and the application of a machine learning algorithm to predict Titanic passenger survival based on given features.
