
# Diabetes Prediction

Steps Performed

- Utilized the following libraries:
  
  - Pandas
  - NumPy
  - StandardScaler
  - Train-Test Split
  - Support Vector Machine (SVM)
  - Accuracy Score
  - Confusion Matrix
  - Classification Report

- Imported and analyzed the diabetes dataset using:
  
  - "head()"
  - "info()"
  - "describe()"
  - "shape()"

- Examined the target variable through:
  
  - "value_counts()"
  - "groupby().mean()"

- Separated input features (X) and output labels (Outcome).

- Applied feature scaling with StandardScaler.

- Performed train-test splitting using:
  
  - "test_size = 0.2"
  - "stratify = y"
  - "random_state = 2"

- Trained an SVM classifier with:
  
  - "kernel = 'linear'"

- Generated predictions on both training and testing datasets.

- Evaluated classification performance using:
  
  - Accuracy Score
  - Confusion Matrix
  - Classification Report

- Developed a prediction system that classifies patients as diabetic or non-diabetic.


# Heart Disease Prediction

Steps Performed

- Imported the required libraries:
  
  - Pandas
  - NumPy
  - LabelEncoder
  - StandardScaler
  - Train-Test Split
  - Support Vector Machine (SVM)
  - Accuracy Score
  - Confusion Matrix
  - Classification Report

- Loaded and explored the heart disease dataset using:
  
  - "head()"
  - "info()"
  - "describe()"
  - "shape()"
  - "isnull().sum()"

- Handled missing values by replacing null values with the median in:
  
  - Trestbps
  - Chol
  - Thalach

- Converted the categorical "Sex" column into numerical values using LabelEncoder.

- Analyzed the target variable using:
  
  - "value_counts()"
  - "groupby().mean()"

- Defined feature variables (X) and target variable (Target).

- Standardized feature values using StandardScaler.

- Split the dataset into training and testing sets using:
  
  - "test_size = 0.2"
  - "stratify = y"
  - "random_state = 2"

- Trained a Support Vector Machine (SVM) classifier using:
  
  - "kernel = 'linear'"

- Generated predictions on training and testing datasets.

- Evaluated model performance using:
  
  - Accuracy Score
  - Confusion Matrix
  - Classification Report

- Developed a prediction system that accepts user input and predicts whether a person has heart disease or not.

- Displayed the prediction result as:
  
  - "No Heart Disease" when prediction = 0
  - "Heart Disease" when prediction = 1


# House Price Prediction

Steps Performed

- Imported required libraries:
  
  - Pandas
  - NumPy
  - StandardScaler
  - Train-Test Split
  - Random Forest Regressor
  - R² Score

- Loaded the house price dataset and explored it using:
  
  - "head()"
  - "shape()"
  - "info()"
  - "isnull().sum()"

- Handled missing values using median imputation.

- Applied the IQR (Interquartile Range) method to detect and remove outliers.

- Defined feature variables (X) and target variable (Price).

- Standardized feature values using StandardScaler.

- Split the dataset into training and testing sets using:
  
  - "test_size = 0.2"
  - "random_state = 2"

- Trained a Random Forest Regressor model using:
  
  - "n_estimators = 200"
  - "max_depth = 10"
  - "random_state = 2"

- Generated predictions on training and testing data.

- Evaluated model performance using the R² Score.

- Built a prediction system that estimates house prices from user-provided inputs.


# Wine Quality Prediction

Steps Performed

- Employed the following libraries:
  
  - Pandas
  - NumPy
  - StandardScaler
  - Train-Test Split
  - Random Forest Regressor
  - R² Score

- Loaded and inspected the wine quality dataset using:
  
  - "head()"
  - "info()"
  - "describe()"
  - "shape()"
  - "isnull().sum()"

- Replaced missing values using median values for:
  
  - Calories
  - pH
  - Sulphates

- Performed outlier detection and treatment using the IQR method.

- Selected wine attributes as features (X) and quality as the target variable (Y).

- Applied StandardScaler to normalize feature values.

- Split the dataset into training and testing sets using:
  
  - "test_size = 0.2"
  - "random_state = 42"

- Trained a Random Forest Regressor model using:
  
  - "n_estimators = 200"
  - "max_depth = 4"
  - "random_state = 42"

- Generated predictions on training and testing data.

- Evaluated model performance using the R² Score.

- Implemented a prediction system that estimates wine quality from user-provided characteristics.


