# 📱 Smartphone Usage vs Academic Performance
### Interactive Data Visualization Dashboard | Power BI | CBP Project

---

## 📌 Project Overview

This project explores how smartphone usage patterns affect the academic performance of students. Using a dataset of 7,500 student records, we built an interactive Power BI dashboard to uncover behavioral correlations between screen time, study habits, sleep, addiction level, and stress.

---

## 🎯 Objective

To analyze and visualize the impact of smartphone usage on student productivity and academic outcomes using data-driven insights — helping identify at-risk behavioral patterns.

---


---

## 📁 Repository Structure
smartphone-usage-academic-performance-powerbi/
│
├── Smartphone_Usage_Dashboard.pbix   ← Main Power BI Dashboard
├── dataset.csv                        ← Source Dataset (7,500 records)
├── screenshots/
│   ├── dashboard_overview.png
│   ├── correlation_analysis.png
│   └── behavioral_analysis.png
├── presentation/
│   └── CBP_Presentation.pptx
└── README.md
---

## 📊 Dataset Description

| Feature | Description |
|--------|-------------|
| `Student_ID` | Unique identifier for each student |
| `Screen_Time_Hours` | Daily smartphone usage (hours) |
| `Study_Hours` | Daily study time (hours) |
| `Sleep_Hours` | Daily sleep duration (hours) |
| `Addiction_Level` | Self-reported addiction score (1–10) |
| `Stress_Level` | Stress index (Low / Medium / High) |
| `Academic_Performance` | GPA or performance score |
| `Risk_Category` | Low / Moderate / High risk classification |

- **Total Records:** 7,500 students
- **Format:** CSV
- **Source:** Behavioral survey dataset

---

## 📈 Dashboard Features

### 🔹 Page 1 — Overview Analysis
- KPI Cards: Average Screen Time, Average Study Hours, Average Sleep
- Risk Distribution Pie Chart (Low / Moderate / High)
- Addiction Level Breakdown (Bar Chart)
- Student count by Stress Level

### 🔹 Page 2 — Correlation Analysis
- Scatter Plot: Screen Time vs Study Hours (with trend line)
- Scatter Plot: Sleep Hours vs Academic Performance
- Correlation matrix visual
- Insight callout cards

### 🔹 Page 3 — Behavioral Analysis
- Addiction Level vs Productivity (Line/Bar combo)
- Stress Level vs Study Hours
- High-risk student segment filter
- Slicers: Gender, Age Group, Stress Level

---

## 🔍 Key Insights

> **1. Screen Time negatively impacts Study Hours**
Higher daily screen time is strongly correlated with lower study hours. Students with 6+ hours of screen time studied 40% less on average.

> **2. Sleep improves Academic Performance**
Students who slept 7–8 hours consistently outperformed those with irregular sleep patterns by a significant margin.

> **3. Addiction reduces Productivity**
Students with addiction scores above 7 showed the lowest study hours and highest stress levels.

> **4. High-Risk Segment Identified**
Approximately 23% of students fall in the "High Risk" category — characterized by high screen time, low sleep, and high addiction scores.

---

## 💡 Recommendations

1. **Set screen time limits** — especially during study hours (6 PM – 10 PM)
2. **Encourage consistent sleep** — 7–8 hours shown to improve performance
3. **Early intervention** — identify high-risk students using addiction + stress indicators
4. **Awareness campaigns** — target students with addiction scores > 6

---

## 📸 Dashboard Preview

### Overview
![Dashboard Overview](<img width="1757" height="910" alt="image" src="https://github.com/user-attachments/assets/1dca99cb-1885-4fe8-b8cf-4625e730350a" />
)

### Correlation Analysis
![Correlation](<img width="1756" height="916" alt="image" src="https://github.com/user-attachments/assets/c5146d80-2cff-4531-a4d3-f57201f3e1c4" />
)

### Behavioral Patterns
![Behavioral](<img width="1764" height="917" alt="image" src="https://github.com/user-attachments/assets/ca92487b-8f84-428f-9c9a-1a9801e797a8" />
)

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Microsoft Power BI Desktop | Dashboard creation & visualization |
| Microsoft Excel / CSV | Data storage and preprocessing |
| DAX (Data Analysis Expressions) | Calculated measures and KPIs |
| Power Query | Data transformation & cleaning |

---

## 🚀 How to Run / Use

1. Download `Smartphone_Usage_Dashboard.pbix`
2. Open it using **[Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/)** (free)
3. If dataset not embedded, also download `dataset.csv` and reconnect source
4. Explore the 3 dashboard pages using slicers and filters

---

> [Live_Dashboard](https://vnrvjietin-my.sharepoint.com/:u:/g/personal/24071a6921_vnrvjiet_in/IQCycdECEeO_TJjhjV3wIfXxASb255XCz32gkRCUizhsGuk?e=PE2xdo)
