SWYNEX-Data-Preparation
Task 1 — Data Preparation | Data Science Internship at SWYNEX Technologies

📊 Dataset
Titanic Dataset — 891 passengers, used to practice data cleaning.

🛠️ Steps Performed
Loaded the dataset using Pandas
Explored the data with .info() and .describe()
Identified missing values: Age (177), Cabin (687), Embarked (2)
Filled Age with the median and Embarked with the mode
Dropped the Cabin column (77% of values missing)
Removed duplicate rows
Saved the cleaned dataset
💻 Tools Used
Python, Pandas, Google Colab
