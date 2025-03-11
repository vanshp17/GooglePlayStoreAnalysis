## **Problem Statement**  
The Google Play Store hosts thousands of apps, making it essential for **developers and investors** to analyze trends and make **data-driven decisions**. This project focuses on **visualizing key insights** from the Play Store dataset using **Power BI**.  

## **Objective**  
Develop an **interactive Power BI dashboard** to provide insights into **app performance, installs, revenue trends, and user behavior** on the Google Play Store.  

## **Project Scope**  
- **Visualize key app metrics** (installs, revenue, ratings).  
- **Analyze app distribution** by category, content rating, and type (Free vs. Paid).  
- **Highlight top-performing apps** based on installs and reviews.  
- **Provide actionable insights** for developers and investors.  

## **Data Collection & Preparation**  
✔ **Dataset:** Google Play Store dataset (~10,841 records, 13 columns).  
✔ **Preprocessing Steps:**  
- Handled **missing values** in the **Rating** column.  
- Converted **Reviews, Installs, and Price** to numeric format.  
- Removed **duplicate app records** for data consistency.  

## **Exploratory Data Analysis (EDA)**  
✔ **Identified outliers** in installs and ratings.  
✔ **Analyzed category-wise distribution** of apps.  
✔ **Detected trends** in paid vs. free app revenues.  

## **Key Features Identified**  
📌 **Top App Categories by Installs:**  
- **Games (28B Installs)**  
- **Communication (17B Installs)**  
- **Tools (11B Installs)**  

📌 **App Type Breakdown:**  
- **Free Apps: 92.67%**  
- **Paid Apps: 7.33%**  

📌 **Top Apps by Installs:**  
- **Google Photos**  
- **Hangouts**  
- **Subway Surfers**  

📌 **App Distribution by Content Rating:**  
- Majority rated **"Everyone"**  
- Fewest apps are **"Unrated"**  

## **Dashboard Visualizations (Power BI)**  
✔ **Category-wise Total Installs** – Bar Chart  
✔ **Percentage of Free vs. Paid Apps** – Pie Chart  
✔ **Sum of Reviews by Category** – Stacked Column Chart  
✔ **Count of Apps by Content Rating** – Tree Map  
✔ **Top Apps by Installs** – Table  
✔ **Count of Apps by Category** – Heatmap  

## **Challenges Faced**  
✔ **Handling outliers** in revenue and installs.  
✔ **Managing data inconsistencies** in category names.  
✔ **Aggregating revenue for paid apps across different price points.**  

## **Tools & Technologies Used**  
- **Power BI** – Dashboard creation  
- **Excel** – Initial data exploration  
- **SQL** – Querying and retrieving cleaned data  
- **Python (Pandas, Matplotlib, Seaborn)** – Data preprocessing and EDA  

## **Results**  
✔ **Developed a dynamic Power BI dashboard** that provides:  
📌 **Market trends & key insights** into app categories and installs.  
📌 **Revenue distribution analysis** for free vs. paid apps.  
📌 **Content rating analysis** to understand audience segmentation.  

## **Future Improvements**  
✔ **Incorporate real-time Play Store data updates.**  
✔ **Use machine learning to predict app success based on ratings & reviews.**  
✔ **Enhance category-wise revenue analysis for better monetization strategies.**  
