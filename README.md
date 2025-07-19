# 🧠 UniAcco Data Analytics Internship Assignment

This repository contains my solution to the Data Analytics Internship assignment given by **UniAcco**. The objective of this task was to analyze user journey and session behavior data to identify drop-offs and provide actionable product insights using Python.

## 📌 Objective

> Identify where users are dropping off in the booking funnel and why.

UniAcco shared two datasets — `Users Data` and `Session Data`. My goal was to:
- Perform exploratory data analysis (EDA)
- Clean and preprocess the data
- Identify drop-off points in the user journey
- Visualize funnel behavior and key user actions
- Generate actionable recommendations

---

## 🧰 Tools & Technologies Used

- 🐍 Python (Pandas, NumPy)
- 📊 Data Visualization: Matplotlib, Seaborn
- 🧼 Data Cleaning: Pandas
- 📒 Jupyter Notebook

---

## 📂 Dataset Overview

1. **Session Data**: Includes user session events like homepage visits, property views, shortlists, bookings, etc.
2. **User Data**: Includes user information such as ID, session timestamps, and device type.

---

## 🧪 Analysis Performed

- ✅ Checked for missing values and cleaned datasets
- 🔄 Merged user and session data for analysis
- 📉 Created funnel stages: Homepage → Property View → Shortlist → Booking
- 📊 Visualized funnel conversion rates and drop-offs
- 🧠 Identified the key pain points leading to funnel drop-off
- 📱 Analyzed engagement by device type and session behavior

---

## 🔍 Key Insights

- The **highest drop-off** occurred between **Property View → Shortlist** stages.
- A significant number of users **never returned** after viewing a property once.
- **Mobile users** had lower conversion compared to desktop, indicating possible UI/UX issues on mobile.
- **One-time sessions** were more likely to abandon the booking flow early.

---

## ✅ Recommendations

- Introduce **smart nudges/reminders** to encourage users to return and shortlist properties.
- Improve mobile site performance and UX to increase engagement.
- Test A/B variants of the property listing page to increase shortlists.
- Add **"Recently Viewed"** or **"Recommended for You"** sections to improve navigation.

---

## 🗂️ Repository Structure

```bash
UniAcco-Dropoff-Funnel-Analysis/
├── 📊 UniAcco.ipynb              # Final notebook with full analysis
├── 📄 README.md                  # Project documentation
├── 📁 data/
│   ├── sessions.csv             # Session-level data
│   └── users.csv                # User-level data
└── 📁 output/
    └── funnel-visualizations/   # Exported charts and plots
```

---

## 📈 Sample Visualizations

- Booking Funnel Drop-off Chart
- Session Frequency Distribution
- Device Type Conversion Comparison

> 📌 *Visuals included inside the Jupyter notebook.*

---

## 🙋‍♀️ About Me

I'm **Nandini Rathod**, a passionate data analyst with strong skills in Python, SQL, and business problem-solving. I enjoy transforming raw data into meaningful insights that drive results.

- 📧 [Email Me](mailto:nandinirathod909@gmail.com)
- 🔗 [LinkedIn](https://www.linkedin.com/in/nandini-rathod-951114248/)

---

## 🔗 Assignment Source

This assignment was provided as part of the **UniAcco Data Analytics Internship** application process.  
Company website: [https://uniacco.com](https://uniacco.com)

---

## ⭐ Final Thoughts

This was an exciting opportunity to apply product analytics and funnel drop-off techniques to a real-world-like dataset. I look forward to future opportunities in solving such data-driven product challenges.

