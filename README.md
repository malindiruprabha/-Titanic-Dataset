# -Titanic-Dataset
Exploring the Titanic Dataset: Feature Engineering &amp; ML in Python
🚢 Titanic Survival Prediction — Data Analysis & Machine Learning

This project explores the famous Titanic dataset to understand what factors influenced passenger survival during the disaster. It is designed for beginners learning data cleaning, visualization, and machine learning using Python, Pandas, and Matplotlib.

📌 Project Objectives

✔ Clean and prepare real-world data
✔ Analyze patterns that affected survival
✔ Visualize findings using data charts
✔ Build simple prediction models

The goal is to transform messy data into meaningful insights and make survival outcomes more understandable.

🧹 1️⃣ Data Cleaning & Preprocessing

Real datasets include missing and inconsistent values. Key steps performed:

Handling missing values in Age, Embarked, and Cabin

Converting categorical features (e.g., Sex) into numerical form

Removing unnecessary or irrelevant columns

Creating new and more useful features such as AgeGroup

➡️ Ensures the dataset is reliable for analysis and modeling.

🔍 2️⃣ Exploratory Data Analysis (EDA)

🎟️ 2. Analyzing Survival Rates by Passenger Class (Pclass) Passenger class played a major role in survival chances during the Titanic disaster. 
📊 Survival rates are analyzed across: 

First Class (Pclass 1) 

Second Class (Pclass 2) 

Third Class (Pclass 3) 

🔍 The analysis shows that passengers in higher classes had significantly higher survival rates, highlighting how socio-economic status influenced access to lifeboats and safety during evacuation.

🚻 Gender (Sex)

Females had a much higher survival rate than males

"Women and children first" strongly reflected in the data

🎂 Age Group (Feature Engineering)

Age is grouped using pd.cut() into:

Group	Range
Infant	0–10
Child	10–12
Teen	12–18
Adult	18–50
Old	50–100

📌 Insight: Infants and children survived more often, while older passengers had lower survival chances.

📊 3️⃣ Data Visualization

To make insights clear, the project includes:

Bar charts → Survival counts by class & gender

Pie charts → Survival proportions

Age-based charts → Survival differences by age groups

Visualization helps reveal patterns not obvious from numbers alone.

🤖 4️⃣ Machine Learning (Beginner Level)

Basic models are trained and evaluated to predict survival using engineered features.
This demonstrates how feature quality impacts prediction accuracy.


