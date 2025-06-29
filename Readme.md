# Customer Churn Prediction

This project analyzes customer churn data and builds a logistic regression model to predict churn.

## Dataset

- **File:** `Customer-Churn.csv`
- Contains customer information such as demographics, account information, and churn status.

## Steps Performed

1. **Import Libraries**  
   Used `numpy`, `pandas`, `matplotlib`, and `seaborn` for data analysis and visualization.

2. **Load the Dataset**  
   Loaded the dataset using pandas.

3. **Data Exploration**  
   Checked for missing values and explored the data structure.

4. **Data Cleaning**  
   - Dropped the `customerID` column.
   - Converted `TotalCharges` to numeric.

5. **Feature Engineering**  
   - Identified categorical and numerical columns.

6. **Data Visualization**  
   - Visualized relationships between numerical features and churn using bar plots and box plots.

7. **Encoding Categorical Variables**  
   - Used `LabelEncoder` to encode categorical columns.

8. **Correlation Analysis**  
   - Plotted a heatmap to visualize feature correlations.

9. **Train-Test Split**  
   - Split the data into training and testing sets (80/20 split).

10. **Feature Scaling**  
    - Standardized numerical features using `StandardScaler`.

11. **Model Building**  
    - Built a logistic regression model using a pipeline with imputation and scaling.
    - Evaluated the model using accuracy and classification report.

## Usage

1. Place `Customer-Churn.csv` in the project directory.
2. Run the notebook `Customer-Churn.ipynb` step by step.
3. Review the output for model performance metrics.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Results

- The logistic regression model achieves an accuracy of approximately 81% on the test set.
- Detailed classification metrics are printed at the end of the notebook.

```
0       0.86      0.90      0.87      1061
1       0.63      0.54      0.58       348

accuracy                           0.81      1409
```
