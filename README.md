# 📊 Twitter Analytics Dashboard using Power BI

This repository contains a Power BI dashboard built to analyze Twitter engagement data under various conditional scenarios. The project includes three interactive and dynamic visualizations, each designed with time-based visibility, custom filters, and business logic to reflect real-time insights.

---

## 📁 Project Structure

- `TwitterAnalyticsDashboard.pbix` – Power BI dashboard file with all 3 tasks implemented.
- `data.xlsx` – Original dataset used in the dashboard.
- `README.md` – Project documentation (you’re reading it!).

---

## ✅ Task Overview

### 🔹 Task 1: High Engagement Tweets Chart
- **Chart Type**: Column Chart
- **Goal**: Display top 10% of tweets by engagement rate.
- **Filters**:
  - Likes > 50
  - Tweet character count < 30
  - Posted on weekdays only
  - Display only between **3 PM to 5 PM IST**
- **Dynamic Behavior**:
  - Graph is hidden outside of 3–5 PM IST.
  - A blank card overlays the chart outside the allowed time window.

---

### 🔹 Task 2: Media Engagement vs Views
- **Chart Type**: Scatter Plot
- **Goal**: Analyze media engagements vs views
- **Highlights**: Tweets with engagement rate > 5%
- **Filters**:
  - Replies > 10
  - Word count > 50
  - Tweet date must be **odd**
- **Dynamic Behavior**:
  - Chart visible only between **6 PM–11 PM IST**
  - Hidden outside the time window

---

### 🔹 Task 3: Average Engagement Rate Trend
- **Chart Type**: Line Chart
- **Goal**: Show average engagement rate trends per month.
- **Separations**: Tweets with vs without media content.
- **Filters**:
  - Tweet engagement rate must be **even**
  - Tweet date must be an **odd** number
  - Tweet character count > 20
  - Remove word `"tweet"` if it contains letter `'C'`
- **Dynamic Behavior**:
  - Chart visible only between **7 AM–11 AM IST** and **3 PM–5 PM IST**

---

## 🛠 Features

- Dynamic chart visibility based on **system time (IST)**
- Time-based filters using DAX measures
- Conditional formatting & flag columns
- Custom Power Query transformations
- Cleaned and enriched dataset using Power Query Editor

---


## 📌 Requirements

- Power BI Desktop (Latest Version)
- Dataset: Twitter export in `.xlsx` format

---

## 🚀 How to Run

1. Clone the repo or download the `.pbix` file.
2. Open in Power BI Desktop.
3. Ensure your system time is set to **IST** (Indian Standard Time) to test visibility filters.
4. Explore each task as per the time windows.

---

## 🙌 Acknowledgements

This project was developed as part of a Power BI learning challenge to showcase dynamic dashboards using real-world Twitter data.

---
