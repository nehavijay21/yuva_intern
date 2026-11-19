Week 1 - Python for Machine Learning & Data Preprocessing

YUVA Internship task: clean and preprocess a sample dataset (Titanic) using Python, NumPy and Pandas.

Files
Week1_Data_Preprocessing.ipynb - full preprocessing code with outputs
titanic_cleaned.csv - final cleaned dataset (775 rows x 10 columns)
missing_heatmap.png, survival_plots.png, correlation.png - EDA plots
Steps done
Loading and inspecting the data
Handling missing values (dropped deck, median for age, mode for embarked)
Removing duplicates and treating outliers (IQR method, capping fare)
Exploratory data analysis
Feature selection (dropped redundant columns, created family_size)
Encoding (binary for sex, one-hot for embarked)
Scaling (Min-Max and Standardization)
