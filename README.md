# 💘 Gen Z Dating App Behavior Analysis  
A Full Data Analysis Project Using Python and Tableau  

---

## 📌 Project Overview  
This project analyzes Gen Z's behavior, preferences, and challenges while using dating apps. The focus is on creating a **highly interactive dashboard** hosted on **Tableau Public**, with filters and insights segmented by **age** and **gender**.

✅ This builds on the accomplishments from the previous project by introducing **interactive filtering** in Tableau.  
⏭️ In the next version, we'll go one step further by using **Action Filters** — where clicking on one chart dynamically updates the others!

---

## 🎯 Key Goals
- Discover the most popular dating apps among Gen Z
- Understand usage frequency and satisfaction levels  
- Explore key challenges in online dating  
- Identify what Gen Z values most in a partner  
- Enable interactivity using filters (age & gender)

---

## 1️⃣ Raw Dataset & Cleaning Process  

**Source**: The dataset was provided as a CSV file including fields like app usage, preferences, communication style, and dating challenges.

**Steps Taken in Python (Pandas):**
- Dropped unnecessary columns (e.g., raw priority text)
- Split the “What are you looking for in a partner?” column into `Priority 1`, `Priority 2`, and `Priority 3`
- Standardized categorical labels (e.g., binary → readable values)
- Handled missing/null values for smoother Tableau integration
- Exported the cleaned dataset as `GenZ_DatingApp_Cleaned.csv`

---

## 2️⃣ Data Upload & Dashboard Creation (Tableau Public)

- The cleaned dataset was imported directly into Tableau
- Age and Gender filters were added to all sheets for interactivity
- Charts and dashboards update **dynamically** based on selected filters  
- Dashboard was published to **Tableau Public** for public access and sharing

**Final Dashboard Includes:**
- 📊 Popular Dating Apps (Bar Chart)
- 🔁 Usage Trends (Bar Chart)
- 💬 Preferred Communication (Pie Chart)
- ❤️ What Gen Z Looks for in a Partner (Treemap)
- ⚠️ Online Dating Challenges (Packed Bubbles)
- 🤝 Satisfaction vs Daily Usage (Heatmap)

🔗 **[View Dashboard on Tableau Public](https://public.tableau.com/app/profile/mantej.singh.samra/viz/InsideGenZsDatingAppBehaviorInsightsThatMatter/Dashboard1?publish=yes)**

---

## 📊 Key Findings & Takeaways

- ✅ OkCupid is the most used dating app  
- ✅ Daily usage is high but doesn't always reflect satisfaction  
- ✅ Gen Z prioritizes **personality** and **values** over appearance  
- ✅ Key concerns include **safety**, **time-wasting**, and **genuine connections**  
- ✅ Users strongly prefer **video calls** and **voice notes** over plain text  

---

## 🔧 Technologies Used

- Python (Pandas) → Data Cleaning  
- Tableau → Data Visualization  
- Tableau Public → Hosting Interactive Dashboard  
- GitHub → Project Documentation  

---

## 🚀 Next Steps

- 🔹 Implement **Action Filters** for click-based dashboard responses  
- 🔹 Add **hover highlights** and sheet swapping for more interactivity  
- 🔹 Explore using NLP for deeper sentiment analysis in open-ended columns  

---

## 🤝 Let's Connect!

- 💼 **LinkedIn**: [mantej-singh-samra](https://www.linkedin.com/in/mantej-singh-samra-087253326)  
- 📂 **GitHub**: [samramantej](https://github.com/samramantej)  
- 📧 **Email**: mantejsamra95@gmail.com
