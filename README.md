# Employee-Data-Analysis-Project
This project focuses on cleaning, transforming, and analyzing employee data using Python. The dataset contains typical HR-related fields such as Age, Salary, Department, Experience, and Performance Ratings. The goal is to prepare the data for meaningful analysis by handling missing, incorrect, and inconsistent values.
Employee Data Analysis Project
This project is focused on analyzing employee-related data to uncover insights, improve data quality, and support data-driven decision-making within an organization. It demonstrates practical data cleaning, transformation, and exploratory analysis techniques using Python and its powerful data handling libraries.

✅ Project Objective
The goal of this project is to work with raw employee data, identify inconsistencies such as missing values, infinite values, negative entries, and outliers, and apply corrective transformations. The cleaned and structured data is then used for various insights such as average salary per department, employee performance trends, and more.

🔧 Key Features
Handling Missing & Null Values:
Replaced NaN and empty entries using appropriate methods like .fillna() with mean, median, or mode depending on the context.

Replacing Infinite and Negative Values:
Detected np.inf, -np.inf, and other logically incorrect values (e.g., negative salary or age) and replaced them with statistically sound values (like the column mean).

Outlier Detection:
Used basic statistical techniques (IQR, bounds) to detect outliers in salary, experience, and ratings, replacing them with mean or median values when appropriate.

String Cleaning & Standardization:
Cleaned and standardized string columns such as "Department", ensuring consistency (e.g., replacing “HR” with “Human Resources”).

Group-based Analysis:
Grouped employees by department and other attributes to compute aggregated metrics such as average salary, average experience, etc.

📈 Tools & Technologies
Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn (optional for visuals)

Environment: Jupyter Notebook / Colab

📚 What I Learned
Real-world datasets often require substantial cleaning before analysis.

Replacing missing or incorrect data can significantly affect the quality of insights.

Data grouping and aggregation are powerful for discovering trends.

Always validate column types before applying logic or calculations.

Feel free to clone, fork, or suggest improvements. This project is a great starting point for anyone interested in data cleaning and real-world data analysis.
