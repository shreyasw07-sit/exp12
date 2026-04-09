# exp12
Shreyas Wani
PRN:25070123131
EXP:12 DATA MANIPULATION AND ANALYSIS
### Technologies Used

Python 3

Pandas: For data manipulation and analysis.

Google Colab: The environment used for execution.

## Dataset Descriptions
### 1. Student Academic Performance

This dataset contains records for 60 students, tracking their gender, department, and grades.

Columns: Student, Gender, Department, Grade.

Departments: CSE, IT, ECE, Mechanical.

Grades: A, B, C.

### 2. E-commerce Order Data

A secondary dataset representing 10 orders to analyze customer behavior and logistics.

Columns: Order_ID, Category, Payment_Method, Delivery_Type, Customer_Type.

Categories: Electronics, Clothing, Grocery.

## Key Analysis & Findings
### Student Data Analysis

Grade Distribution: Grade B is the most common (40%), followed by Grade A (36.67%) and Grade C (23.33%).

Department Performance: The CSE department has the highest percentage of 'A' grades at 65%, while the Mechanical department recorded 0% 'A' grades in this sample.

Gender Analysis: Female students in this dataset achieved more 'A' grades (14) compared to male students (8).

### E-commerce Insights

Payment Preferences: There is a perfect correlation between category and payment method in this sample:

Electronics: 100% UPI

Clothing: 100% Card

Grocery: 100% Cash

Customer Retention: The dataset is split between New and Returning customers across different delivery types (Express vs. Standard).

## Operations Performed
The following pandas methods were utilized throughout the notebook:

df.info() & df.shape: Checking data structure and dimensions.

df.value_counts(): Calculating frequencies and percentages.

pd.crosstab(): Analyzing relationships between two categorical variables.

df.groupby(): Aggregating data based on specific categories.

df.isnull().sum(): Verifying data cleanliness (0 null values found).

df.sort_values(): Organizing data for better readability.

## How to Use
Ensure you have pandas installed: pip install pandas.

Upload Expt11.csv to your environment (required for the first section).

Run the cells sequentially to observe the data summaries and cross-tabulations.
