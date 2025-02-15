# Bank-Marketing-Data-Analysis

### Dataset: 
[Here](https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset/data)

## 1️⃣ Understanding the Data
- **Dataset Overview**: The dataset contains information about bank telemarketing campaigns.
- **Objective**: Identify patterns that influence whether a customer subscribes to a term deposit (`y` column).
- **Key Features**:
  - `age`, `balance`, `duration` (Numerical)
  - `job`, `marital`, `education`, `contact` (Categorical)
  - `campaign`, `pdays`, `previous` (Marketing-related)
  
## 2️⃣ Data Preprocessing
- **Handled Missing Values**
  - No missing values
  
- **Outlier Handling**
  - Detected outliers using **box plots**.
  - Capped extreme values for `balance`, `campaign`, and `duration`.
  
## 3️⃣ Exploratory Data Analysis (EDA)

### **Univariate Analysis**
- **Numerical Features**:
  - Used **histograms** to check distributions.
  - Used **box plots** to visualize outliers.
- **Categorical Features**:
  - Used **bar charts** to analyze category distributions.
 
### **Bivariate Analysis**
- **Numerical vs Numerical**:
  - Used **correlation heatmap** to identify relationships.
  
- **Numerical vs Categorical**:
  - Used **box plots** to compare numerical features across `y` (Deposit/Not Deposit).
  - Used **violin plots** for `duration` vs `y`.
  
- **Categorical vs Categorical**:
  - Used **stacked bar charts** to analyze relationships.

## 5️⃣ Next Steps
- Perform feature selection.
- Encode categorical variables.

📌 **Key Findings**
- **Longer call durations** lead to a higher chance of deposit.
- **Job type** significantly influences subscription.
- **Highly correlated features** need to be removed for better model performance.
