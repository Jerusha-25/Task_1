#🧹 Task 1: Data Preprocessing on Titanic Dataset

🎯 Objective
The aim of this task is to perform fundamental data preprocessing techniques on the Titanic dataset to prepare it for machine learning applications. The focus is on cleaning, encoding, scaling, and handling outliers in the dataset.

🧰 Tools Used
Python
Pandas – for data manipulation
NumPy – for numerical operations
Matplotlib / Seaborn – for data visualization

🔧 Steps Performed
1.Import and Explore Dataset
Loaded the Titanic dataset and explored basic information using .info(), .head(), and .isnull().sum().

2.Handle Missing Values
Filled missing numerical values using mean or median depending on the distribution.

3.Encoding Categorical Variables
Used Label Encoding and One-Hot Encoding to convert categorical columns into numerical formats.

4.Normalize/Standardize Numerical Features
Applied StandardScaler or MinMaxScaler to scale numerical values for consistent range and distribution.

5.Visualize and Remove Outliers
Used boxplots to visualize outliers.
Applied the IQR method to remove outliers from important numeric columns.

✅ Outcome
Cleaned and structured dataset ready for further machine learning tasks with all key preprocessing steps completed.
