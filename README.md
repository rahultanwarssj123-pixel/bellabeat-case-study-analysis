# Bellabeat Case Study Analysis

## 1. Business Task

Bellabeat aims to understand how users engage with smart fitness devices in order to improve user retention and product engagement.
The objective of this analysis is to identify behavioral patterns in user activity and provide data-driven recommendations.

---

## 2. Data Source

* Fitbit Fitness Tracker Dataset (Kaggle)
* The dataset includes daily activity records such as:

  * Steps
  * Calories burned
  * Distance
  * Activity intensity levels

*Note: The full raw dataset is not uploaded due to size constraints.*

---

## 3. Data Preparation & Cleaning

* Standardized date formats for consistency
* Created derived columns:

  * **DayOfWeek**
  * **DayNumber**
* Verified dataset for missing and duplicate values
* Removed or ignored irrelevant/zero-value columns where applicable
* Prepared structured tables for pivot-based analysis

---

## 4. Exploratory Analysis

### 4.1 Activity Trends by Day

* Calculated average steps and calories across weekdays
* Observed variation in activity levels across the week
* Activity shows a slight increase toward the end of the week

---

### 4.2 Activity Level Distribution

Users were categorized into:

* Active
* Moderately Active
* Inactive

Findings:

* ~65–70% of users fall into **inactive or moderately active categories**
* Only a smaller segment qualifies as highly active

---

### 4.3 User Consistency Analysis

Users were classified based on frequency of activity:

* High Consistency
* Moderate Consistency
* Low Consistency

Findings:

* Majority of users show **moderate consistency**
* Very few users maintain **high consistency**
* A small segment shows **low engagement**

---

## 5. Key Insights

* A significant portion of users are not highly active, indicating **low overall engagement levels**
* User behavior is **inconsistent**, with limited habit formation
* Engagement tends to **increase toward weekends**, suggesting behavioral patterns tied to weekly schedules
* Moderate users represent the **largest opportunity segment** for improvement

---

## 6. Business Recommendations

* **Improve engagement of inactive users**
  Use personalized notifications and reminders to encourage daily activity

* **Increase user consistency**
  Introduce streak-based features (daily goals, rewards, badges) to promote habit formation

* **Leverage high-engagement periods**
  Launch challenges or campaigns during weekends to maximize participation

* **Convert moderate users into active users**
  Target this segment with achievable goals and progress tracking

---

## 7. Tools Used

* Google Sheets (Data Cleaning, Pivot Tables, Analysis)
* Excel (Data Handling and Calculations)
* GitHub (Project Documentation and Version Control)

---

## 8. Repository Contents

* `Fitbit data.xlsx` → Cleaned dataset and analysis
* `Bellabeat Usage Analysis.pdf` → Detailed analysis report
* `Screenshots` → Charts and visual insights

---

## 9. Conclusion

This analysis highlights that user engagement is currently limited by inconsistent behavior and a high proportion of low-activity users.
By focusing on habit-building features and targeted engagement strategies, Bellabeat can significantly improve user retention and overall product value.

