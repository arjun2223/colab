# 📊 Insurance Data Analysis with Python 🐍  

Welcome to this project! 🎉  
In this notebook, we explore the famous **Insurance dataset** using **Pandas** in Google Colab.  

---

## ✨ Project Highlights  
- 📥 Load dataset (`insurance.csv`)  
- 👀 Explore data with `head()`, `tail()`, and `.info()`  
- 📐 Get summary statistics with `.describe()`  
- 🔍 Analyze key features like:  
  - Age 👨‍👩‍👧‍👦  
  - Sex 🚹🚺  
  - BMI ⚖️  
  - Children 👶  
  - Smoker status 🚬  
  - Region 🌍  
  - Charges 💰  

---

## 📂 Dataset Overview  

- **Rows:** 1338  
- **Columns:** 7  
- **Features:**  

| Column   | Type    | Description |
|----------|---------|-------------|
| age      | int64   | Age of the person 👤 |
| sex      | object  | Gender 🚹🚺 |
| bmi      | float64 | Body Mass Index ⚖️ |
| children | int64   | Number of dependents 👶 |
| smoker   | object  | Smoking status 🚬 |
| region   | object  | Residential area 🌍 |
| charges  | float64 | Medical cost 💰 |

---

## ▶️ Example Code  

```python
import pandas as pd  

# Load dataset
df = pd.read_csv("insurance.csv")

# Show first 5 rows
print(df.head())

# Dataset info
df.info()

# Summary statistics
print(df.describe())

# Shape of dataset
print(df.shape)
📊 Sample Output
Shape: (1338, 7)

Average Age: ~39 years

Average BMI: ~30.66

Average Charges: ~$13,270 💵

🚀 Future Ideas
Add data visualization with Matplotlib & Seaborn 📈

Build ML model to predict charges 🤖

Create interactive dashboard with Streamlit or Plotly 🌐

🌟 Tools Used
🐍 Python

📘 Pandas

📓 Google Colab
