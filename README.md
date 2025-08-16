# 📊 Netflix Content Insights Dashboard

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow)  
![Dataset](https://img.shields.io/badge/Dataset-Kaggle-blue)  
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Overview
An **interactive Power BI dashboard** that analyzes and visualizes Netflix’s movie & TV show catalog.  
It uncovers **trends in genres, release years, and content types** to help guide content curation and marketing strategies.  

📂 **Live Dataset:** [Netflix Movies and TV Shows – Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)  

---

## 🎯 Problem Statement
Netflix’s growing library makes it **hard to quickly see trends** in content distribution by type, genre, and release year.  
Without visual insights, **decision-making** in marketing and production strategy becomes inefficient.

---

## 🎯 Objectives
- 📺 Compare **Movies vs TV Shows** distribution.
- 🎭 Identify **top genres** and niche categories.
- 📈 Track **annual content growth** (2000–2020).
- 🕵️ Genre deep-dive (*Murder Mystery*).
- 🖱️ Enable **interactive exploration** via filters.

---

## 📊 Dataset Details
- **Source:** Kaggle – Netflix Movies and TV Shows  
- **Columns:** `show_id`, `type`, `title`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`

---

## 🛠 Data Preparation
**Power Query** transformations:
- ✅ Promoted headers, trimmed spaces, renamed columns.
- ✅ Changed data types.
- ✅ Filled missing `director` & `cast` values.
- ✅ Kept only relevant columns.

**DAX Measures**:
- 📆 `release_year` extraction.
- 🔍 `is_murder_mystery` flag.
- 📊 Measures: `Total_Titles`, `Total_Movies`, `Total_TV_Shows`.

---

## 🔍 Key Insights
📌 **8,000+ Titles** – 68% Movies, 32% TV Shows  
🎭 **Top Genres:** Drama (1,509), Comedy (1,122), Documentary (815)  
📈 **Content Boom:** 2015–2019  
🕵️ *Murder Mystery* = small percentage of catalog  
📉 **2020 Dip** – Likely due to COVID-19 production delays  

---

## 💡 Recommendations
- Promote **Drama** & **Comedy** (top performers).  
- Grow niche genres like **Anime** & **Classic Movies**.  
- Address content drop reasons (e.g., pandemic).  
- Use genre trends to **guide licensing & production**.

---

## 📈 Tools & Tech
- **Data Source:** Kaggle CSV Dataset  
- **Cleaning:** Power Query  
- **Modeling:** DAX  
- **Visualization:** Power BI  

---

## 📷 Dashboard Preview
<img width="1310" height="737" alt="image" src="https://github.com/user-attachments/assets/3709ea41-e841-4ad0-995d-1fff3d449dda" />


---

## 🚀 How to Use
1. 📥 Download dataset from Kaggle.  
2. 📂 Open `.pbix` file in **Power BI Desktop**.  
3. 🔄 Refresh to load latest data.  
4. 🎯 Use filters for year, genre, and type.  

---
