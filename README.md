# Linear-Regression-ML-Algorithm

### 📘 Definition:

Linear Regression is a supervised machine learning algorithm used for predicting a continuous dependent variable 

based on one or more independent variables (features). It models the relationship between variables by fitting a 

linear equation to observed data.


### What I have done in this project ---

### 1. Load Dataset

**Objective:** Import the dataset to work with.

**Sources:** CSV, Excel, SQL, or web-based datasets.

**Tools:** pandas.read_csv() or similar functions.

### 2. View / Preprocess Dataset

**Objective:** Understand the structure of data and clean it.

**🔍 Data Exploration**

View top rows: data.head()

Data types: data.dtypes

Shape: data.shape

Summary statistics: data.describe()

**🧹 Data Cleaning**

Handle missing values: fillna(), dropna()

Remove duplicates

Convert categorical to numeric (if needed): One-hot encoding or Label encoding

**📐 Feature Selection**

Choose relevant independent variables (features) and the dependent variable (target).

### 3. Split Dataset

**Objective:** Separate data into training and testing sets to evaluate generalization.

**Tool:** train_test_split() from sklearn.model_selection

### 4. Build the Linear Regression Model

**Objective:** Train the model on the training data.

**Tool:** LinearRegression from sklearn.linear_model

### 5. Test / Evaluation

**Objective:** Make predictions and compare them to actual values.

### 6. Performance Analysis

**Objective:** Quantify how well the model performs.

**📏 Common Metrics:**

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R-squared Score (R²)

| Step                 | Description                                  |
| -------------------- | -------------------------------------------- |
| Load Dataset         | Import using pandas or other libraries       |
| View/Preprocess      | Clean data, handle nulls, transform features |
| Split Dataset        | Training vs testing data                     |
| Build Model          | Train Linear Regression on training data     |
| Test/Evaluate        | Predict and compare with actual test data    |
| Performance Analysis | Use MAE, MSE, RMSE, R² for evaluation        |
