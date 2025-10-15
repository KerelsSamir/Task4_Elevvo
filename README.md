# 🚢 Exploratory Data Analysis (EDA) on Titanic Dataset  

---

## 📘 Project Overview  
This project performs an **Exploratory Data Analysis (EDA)** on the famous **Titanic dataset**, aiming to understand the characteristics of passengers who **survived** versus those who did not.  
The main objective is to identify **key factors and correlations** influencing survival outcomes.

---

## 🧹 Data Processing & Cleaning  

During the initial data inspection, several missing values were identified.  
The following data cleaning steps were performed:  

- **Dropped Column:**  
  - `Cabin` — removed entirely due to a large proportion of missing values.  

- **Imputation:**  
  - `Age` — missing values filled using the **median** age.  
  - `Embarked` — missing values filled using the **mode** (most frequent value).  

- **Final Check:**  
  - After cleaning, **no missing values** remained in the processed dataset.  

---

## 🔍 Exploratory Data Analysis (EDA) & Key Findings  

### 1️⃣ Survival by Sex  
- Strong correlation between **Sex** and **Survival**.  
- **Females** had a significantly higher survival rate than males.  
- This aligns with the _“women and children first”_ policy.  

📊 **Conclusion:** Gender played a decisive role in survival chances.  

---

### 2️⃣ Survival by Ticket Class (Pclass)  
- **First Class (Pclass 1)** passengers had the **highest survival rate** — more survivors than casualties.  
- **Third Class (Pclass 3)** passengers had the **lowest survival rate** and **highest number of casualties**.  

📈 **Conclusion:** Higher socio-economic status (First Class) increased the probability of survival.  

---

### 3️⃣ Survival Count by Embarkation Port  
- **Cherbourg (C)**: Highest proportion of survivors.  
- **Southampton (S)**: Lowest proportion of survivors but had the most passengers.  

🗺️ **Insight:** The embarkation port shows a mild relationship with survival rates.  

---

### 4️⃣ Fare Distribution by Survival  
A **violin plot** comparing fares shows that:  
- Survivors generally paid **higher fares**, with a broader distribution toward higher ticket prices.  

💡 **Conclusion:** Higher fares correspond to **higher-class tickets**, reinforcing the Pclass–Survival relationship.  

---

### 5️⃣ Correlation Heatmap (Numerical Features)  
A correlation analysis among numerical features revealed:  

| Feature | Correlation with Survived | Insight |
|----------|----------------------------|----------|
| **Pclass** | -0.34 | Lower class → lower survival chance |
| **Fare** | +0.26 | Higher fare → higher survival chance |
| **Age** | -0.06 | Weak negative correlation |

📊 **Conclusion:** Passenger class and fare have the strongest correlations with survival.  

---

## 🧠 Summary of Insights  

| Key Factor | Impact on Survival |
|-------------|--------------------|
| **Sex** | Females survived more frequently |
| **Pclass** | First Class passengers had the highest survival rate |
| **Fare** | Higher fares correlated with better survival chances |
| **Embarked** | Cherbourg passengers had slightly higher survival rates |
| **Age** | Minimal correlation observed |

✅ **Overall Conclusion:**  
The EDA confirms that **Sex**, **Passenger Class (Pclass)**, and **Fare** are the most influential factors determining a passenger's survival.  
Females and First-Class passengers had significantly higher survival probabilities.  

---

## 🛠️ Technologies Used  

| Tool / Library | Purpose |
|-----------------|----------|
| **Python** | Core programming language |
| **Pandas** | Data cleaning & manipulation |
| **NumPy** | Numerical computations |
| **Matplotlib / Seaborn** | Data visualization |
| **Plotly** | Interactive visual exploration |

---

## 📈 Summary  
This project showcases how **Exploratory Data Analysis** helps uncover meaningful insights from real-world datasets.  
Through visualization and statistical interpretation, the analysis highlights how social and economic factors influenced survival on the Titanic.

---

### 🧾 Author  
**Kerels Samir**  

---
