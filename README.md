# 🚢 Titanic Survival Analysis — Data Analysis Project

## 📌 Project Overview
This project analyzes the famous **Titanic dataset (train.xlsx)** to uncover insights into survival patterns during the 1912 disaster. The goal was to identify **key factors that influenced passenger survival** using Data Analytics techniques, including data cleaning, statistical analysis, visualization, and storytelling.

The final output is presented via:
- **Google Sheets (Data processing, analysis, visualization)**
- **Power BI Dashboard (`titanic dashboard.pbix`)**

---

## 📊 Key Business Questions Answered
✔ What percentage of passengers survived the tragedy?  
✔ Did gender influence survival rate?  
✔ Did passenger class (1st, 2nd, 3rd) impact survival chances?  
✔ Were younger passengers more likely to survive?  
✔ How did fare and socio-economic status relate to survival?

---

## 🗂 Project Structure

| File / Sheet | Purpose |
|------------|--------|
| `train.xlsx` | Raw Titanic dataset containing survival outcomes |
| `Google Sheet → Raw Data` | Original dataset (untouched) |
| `Google Sheet → Analysis` | Calculated statistics, cleaned age column, pivot tables, survival metrics |
| `Google Sheet → Dashboard` | Charts, insights, conclusions, storytelling |
| `titanic dashboard.pbix` | Interactive Power BI dashboard for deeper insights |

---

## 🧮 Analysis Includes
### 1️⃣ **Data Classification**
| Column | Type |
|--------|------|
| Survived | Binary / Nominal |
| Pclass | Ordinal |
| Sex | Nominal |
| Age | Ratio |
| Fare | Ratio |

### 2️⃣ **Descriptive Statistics**
- Mean & Median Age
- Mean & Median Fare (shows right-skewed distribution)
- Standard Deviation & Variance

### 3️⃣ **Distribution Analysis**
- Survival (Bernoulli Distribution, probability `p`)
- Age histogram (checked for bell curve / normality)

### 4️⃣ **Insights**
- Survival by gender
- Survival by passenger class
- Average age comparison: survivors vs non-survivors
- Age missing data handled using **Group Median Imputation (based on Pclass + Sex)**

---

## 💡 Key Findings (Story & Conclusion)
- **Females survived significantly more than males**
- **1st class passengers had the highest survival rate, 3rd class the lowest**
- Socio-economic status strongly influenced survival
- The average survivor was younger than non-survivors
- Fare distribution was highly skewed due to a few expensive tickets

---

## 🛠 Tools Used
- Google Sheets (Data cleaning, formulas, pivot tables, charts)
- Power BI (Dashboards, visual storytelling)
- Excel (Dataset management)

---

## 📎 Submission Link
🔗 *Google Sheet :* — https://docs.google.com/spreadsheets/d/1jOYaVrhoQ6rXooFY-Ch4lUm_bsTjGDhHNkhWI0GsZd8/edit?usp=sharing  

---

## ✍ Author
**Piyush Goyal**  
JECRC Foundation — C Programming & Data Analysis  
Mentor: *Marval Card*

---
⭐ *If you like this project, give it a star!*
