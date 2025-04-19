 ## 🧠 Task 02: Data Cleaning & Exploratory Data Analysis (EDA)

---

### 📌 **Task Objective**
Perform data cleaning and exploratory data analysis (EDA) on a dataset of your choice (Titanic Dataset recommended).  
🔍 Explore relationships between variables and identify meaningful patterns and trends in the data.

---

### 🗂️ **Dataset Used**
- **Name:** Titanic Dataset  
- **Source:** [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/data)  
- **Features Include:**  
  - `Survived`, `Pclass`, `Name`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, `Embarked`, etc.

---

### 🧰 **Tools & Libraries**
- **Platform:** Google Colab  
- **Language:** Python  
- **Libraries Used:**
  - `pandas` for data manipulation
  - `numpy` for numerical operations
  - `matplotlib`, `seaborn` for static visualizations
  - `plotly` for interactive visualizations

---

### 🧹 **Data Cleaning Steps**
- Removed irrelevant columns: `Cabin`, `Ticket`, `Name`
- Handled missing values in `Age` and `Embarked`
- Converted categorical features (`Sex`, `Embarked`) using label/one-hot encoding
- Verified data types and fixed inconsistencies

---

### 📊 **Exploratory Data Analysis (EDA)**
#### 🔍 Univariate Analysis
- Distribution of survival (`Survived`)
- Age distribution of passengers
- Count of passengers by `Pclass`, `Sex`, and `Embarked`

#### 🔗 Bivariate Analysis
- Survival rate vs Gender
- Survival rate across Passenger Classes
- Impact of Fare on survival
- Age distribution based on survival

#### 🔥 Correlation Analysis
- Heatmap of numeric features
- Pearson correlation coefficients

#### 📈 Visuals Created
- Count plots
- Histograms & KDE plots
- Box plots
- Pie charts & bar graphs
- Interactive plotly charts

---

### 📌 **Key Insights**
- 🎯 Females had significantly higher survival rates.
- 🛳️ Passengers in 1st class had a better chance of survival.
- 👶 Children had slightly higher survival rates than adults.
- 💰 Higher fare correlated with better chances of survival.

---


