# 🐿️ NYC Squirrel Census Analysis

This project explores the **2018 Central Park Squirrel Census dataset**.  
The goal was to clean the data, handle missing values, and analyze squirrel sightings to uncover patterns in their activity.

---

## 📌 What I Did  
- **Data Cleaning**
  - Dropped nearly empty columns (`Hectare Conditions Notes`, `Litter Notes`).
  - Filled missing categorical values (`Litter Notes`, `Other Animal Sightings`, `Hectare Conditions`).
  - Filled missing numerical values (`Total Time of Sighting`) with the **mode**.
  - Converted `Date` from `mmddyy` format into a proper datetime and extracted the **Day**.  

- **Exploratory Data Analysis (EDA)**
  - Visualized **top 10 hectares** with most squirrel activity.  
  - Compared **AM vs PM** sessions (50/50 split).  
  - Checked **hectare conditions** (`Busy`, `Calm`, etc.) and their squirrel counts.  
  - Analyzed daily trends → peak activity on **Oct 13, 2018**.  
  - Looked at **litter levels** and squirrel presence.  
  - Compared sightings by **number of observers (sighters)** using bar and scatter plots.  

---

## 📊 Key Insights  
- Most squirrel sightings were in **Busy** and **Calm** areas.  
- Sessions were **evenly balanced** between AM and PM.  
- **October 13th** had the highest squirrel activity (430+ sightings).  
- Most data came from **single observers**, though group sightings showed higher variation.  
- Litter presence (`None`, `Some`, `Abundant`) was recorded but didn’t dominate the dataset.  

---

## 📚 What I Learned  
- How to handle missing values using **drop**, **fillna**, and **mode**.  
- Converting and working with **dates** in pandas (`to_datetime`, `dt.day`).  
- Creating meaningful **visualizations** (bar plots, pie charts, line plots, scatter plots).  
- The importance of documenting analysis with **markdown + comments** so results tell a story.  
- How structured notebooks can feel like **mini research reports** when organized properly.  

---

## 🚀 Next Steps  
- Explore relationships between squirrel behavior and **weather data**.  
- Model daily activity trends to see if there are **predictable patterns**.  
- Use clustering to group squirrels by behavior and location.  

---

## 💬 Feedback  
If you notice any mistakes or have suggestions for improvements, feel free to open an issue or drop feedback — I’d love to learn and make this better!  

---

👩‍💻 **Author:** Bushra 🪐  
