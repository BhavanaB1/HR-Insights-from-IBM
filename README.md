IBM HR Analytics - Employee Attrition Exploration

This project performs an exploratory data analysis (EDA) on the IBM HR Analytics Employee Attrition dataset. The goal is to uncover patterns and insights related to employee turnover using visualizations and basic statistical analysis.

📦 Dataset
Source: Kaggle - IBM HR Analytics Attrition Dataset
Accessed via: kagglehub

📚 Libraries Used
pandas for data manipulation
numpy for numerical operations
matplotlib and seaborn for visualization
warnings to suppress unnecessary warnings

🧹 Data Loading & Cleaning
Dataset loaded into a Pandas DataFrame
df = pd.read_csv(path + '/WA_Fn-UseC_-HR-Employee-Attrition.csv')
Basic inspection with .head() and .describe()
Null value check confirms no missing data

📊 Visualizations
The project includes several visualizations to explore various aspects of the dataset:
Employee Count by Job Role
Average Monthly Income by Gender
Monthly Income Distribution
Monthly Income by Job Level
Years at Company by Gender and Marital Status
Attrition by Overtime Status
Correlation Heatmap of Numeric Features

🔍 Insights
Higher attrition is observed among employees who frequently work overtime.
Job level and income are positively correlated.
Marital status and gender influence the number of years employees stay with the company.
