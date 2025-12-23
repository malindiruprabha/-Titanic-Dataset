# -Titanic-Dataset
Exploring the Titanic Dataset: Feature Engineering &amp; ML in Python
🚢 Exploring the Titanic Dataset: Feature Engineering & Machine Learning in Python (Beginner Level) The Titanic dataset is one of the most popular datasets used to introduce data analysis, feature engineering, and machine learning. It contains real passenger information from the Titanic disaster, making it ideal for learning how data can be cleaned, analyzed, visualized, and used to predict outcomes. In this project, we explore how different passenger features influenced survival using Python, Pandas, Matplotlib, and basic machine learning concepts.

🧹 1. Data Cleaning: Fixing the Titanic Data Before It Sinks Our Analysis
Real-world data is rarely perfect, and the Titanic dataset is no exception. Before performing any analysis or building machine learning models, the dataset must be cleaned and prepared. 
🔧 Key data cleaning steps include: 
Handling missing values (such as Age and Cabin) Removing or fixing incorrect and duplicate records Converting categorical data (Sex, Embarked) into a usable format Dropping unnecessary columns that do not contribute to analysis 
✔️ This step ensures the dataset is accurate, consistent, and ready for meaningful analysis and predictions.

🎟️ 2. Analyzing Survival Rates by Passenger Class (Pclass) Passenger class played a major role in survival chances during the Titanic disaster.
📊 Survival rates are analyzed across:
First Class (Pclass 1)
Second Class (Pclass 2) 
Third Class (Pclass 3) 
🔍 The analysis shows that passengers in higher classes had significantly higher survival rates, highlighting how socio-economic status influenced access to lifeboats and safety during evacuation.

📈 3. Make It Attractive: Visual Thinking with Charts To make insights easier to understand, data visualization techniques such as bar charts and pie charts are used.

📊 3.1 Survival Rates by Passenger Class (Pclass) 
Bar charts compare survival counts across classes
Pie charts visually show survival proportions 
👁️ These visuals help quickly identify patterns that may not be obvious from raw data.

🚻 3.2 Analyzing Survival Rates by Gender (Sex) 
Gender is analyzed to understand its impact on survival. 🔎 Key observations from the dataset:
Female passengers show a lower survival rate
Male passengers show a higher survival rate 
📌 This indicates that gender plays a significant role in survival outcomes and is an important feature for analysis and machine learning predictions.

🎂 3.3 Analyzing Survival Rates by Age (Age Grouping) 
To better understand how age influenced survival, passengers’ ages are grouped into meaningful categories using feature engineering. Instead of analyzing individual ages, age groups are created to make patterns easier to identify and visualize.
🧮 Age groups created using pd.cut():
👶 Infant (0–10 years) 
🧒 Child (10–12 years) 
🧑 Teen (12–18 years) 
👨‍👩‍👧 Adult (18–50 years) 
👴 Old (50–100 years) 
This new column, AgeGroup, helps compare survival rates across different life stages.
📌 Key Insights: 
Infants and children show higher survival rates 
Adults have moderate survival chances due to their large numbers onboard 
Older passengers show lower survival rates, likely due to mobility and health limitations
✅ Grouping ages makes the analysis clearer and improves feature quality, helping machine learning models perform better
