House Price Prediction

Steps Performed

1. Imported required libraries:
   
   - Pandas
   - NumPy
   - Scikit-learn
   - StandardScaler
   - Train-Test Split
   - Random Forest Regressor
   - R² Score

2. Loaded the house price dataset using Pandas.

3. Performed exploratory data analysis:
   
   - Viewed dataset using "head()"
   - Checked dataset shape
   - Used "info()" to inspect data types
   - Checked missing values using "isnull().sum()"

4. Handled missing values by filling them with the median.

5. Detected and removed outliers using the IQR (Interquartile Range) method.

6. Selected features (X) and target variable (Price).

7. Applied feature scaling using StandardScaler.

8. Split the dataset into training and testing sets using an 80:20 ratio.

9. Trained a Random Forest Regressor model with:
   
   - n_estimators = 200
   - max_depth = 10
   - random_state = 2

10. Generated predictions for training and testing data.

11. Evaluated model performance using the R² Score.

12. Built a prediction system that accepts new house details and predicts the house price.
