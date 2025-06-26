# Task 2 – Exploratory Data Analysis (EDA)

## 📌 Objective
To explore and understand the Titanic dataset using summary statistics and visualizations. The goal is to identify patterns, trends, and relationships among features that can guide further modeling.

---

## 🛠 Tools Used
- Python
- Pandas
- Seaborn
- Matplotlib
- Plotly

---

## 📊 Steps Performed

### 1. Summary Statistics
- Calculated mean, median, and standard deviation for numeric features.
- Used `df.describe()` to get a summary of the central tendency and dispersion of the data.

### 2. Visualizations
- Created bar charts to understand the distribution of categorical features like 'Sex', 'Pclass', 'Survived', and 'Embarked'.
- Utilized histograms to visualize the distribution of 'Age' and 'Fare'.
- Explored relationships using a pairplot and a heatmap to identify correlations between features.

### 3. Insights
- Found that females had a higher survival rate compared to males.
- Passengers in higher classes had a higher survival rate.
- There were more males than females on the ship.
- Most passengers embarked from Southampton.
- The majority of passengers were in the 3rd class.
- The average age of passengers was around 30 years.
- The average fare was around 32.20.
- There was a high correlation between 'Fare' and 'Pclass'.
- There was a low correlation between 'Age' and 'Survived'.
- There was a low correlation between 'Sex' and 'Survived'.


