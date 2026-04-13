# 🔮 AstroSage Call Center Analytics Dashboard

## 📌 Project Overview
This project focuses on analyzing and optimizing the **AstroSage Call & Chat Center operations** using Excel-based data analytics.  
The goal is to derive actionable insights to improve **operational efficiency, customer satisfaction, and profitability**, and to recommend how a **₹1 Crore investment** should be allocated.

---

## 🎯 Objectives
- Analyze call and chat data to identify performance trends
- Evaluate **agent (guru) performance**
- Measure **customer satisfaction**
- Track **revenue and operational costs**
- Identify **repeat customers**
- Provide **data-driven investment recommendations**

---

## 📂 Dataset Description
The dataset contains **31 attributes**, including:

| Category | Columns |
|--------|--------|
| Identification | `_id`, `uid`, `guru`, `guruName` |
| Time Data | `createdAT`, `callDate`, `callMonth`, `callHour` |
| Call Info | `consultationType`, `callStatus`, `chatStatus` |
| Duration | `timeDuration`, `chatSeconds`, `userOnCallDuration` |
| Financial | `amount`, `netAmount`, `astrologersEarnings` |
| Performance | `rating`, `astrologerCallStatus` |
| Other | `region`, `website`, `refundStatus` |

---

## 🧹 Data Cleaning Steps
- Filled missing categorical values with **"Not Applicable"**
- Replaced missing numerical values with **0**
- Standardized text using **TRIM & PROPER**
- Created structured date columns:
  - `callDate`
  - `callMonth`
  - `callHour`

---

## 📊 Key KPIs
- 📞 Total Calls
- 📅 Average Daily Calls
- 💰 Total Revenue
- 💸 Operational Cost
- ⭐ Average Customer Rating
- 🔁 Repeat Caller Percentage

---

## 📈 Dashboard Components

### 🔹 1. Call Trends
- **Line Chart** → Daily Call Volume (`callDate`)
- **Column Chart** → Monthly Call Volume (`callMonth`)

### 🔹 2. Financial Analysis
- **Pie Chart** → Revenue by `consultationType`
- **Column Chart** → Monthly Operational Cost

### 🔹 3. Agent Performance
- **Bar Chart** → Calls handled per `guruName`
- **Bar Chart** → Average Rating per `guruName`

### 🔹 4. Customer Insights
- **Donut Chart** → Repeat vs New Customers (`uid`)
- **Line Chart** → Monthly Satisfaction Trend
- **Scatter Plot** → `timeDuration` vs `rating`

---

## 🎛️ Interactive Features
- Slicers used for:
  - `callMonth`
  - `guruName`
  - `consultationType`
  - `region`
  - `callStatus`
  - `chatStatus`

---

## 🔍 Key Insights
- Peak call volumes occur during specific months and hours
- Some gurus consistently outperform others in customer ratings
- Repeat customers contribute significantly to total interactions
- Longer call durations tend to correlate with higher satisfaction
- Operational costs vary significantly across months

---

## 💡 Business Recommendations

### 💰 ₹1 Crore Investment Allocation
| Area | Allocation |
|------|-----------|
| Technology Upgrade | ₹40 Lakhs |
| Hiring Agents | ₹35 Lakhs |
| Training Programs | ₹25 Lakhs |

### 📌 Strategic Actions
- Implement AI-based call routing systems
- Train low-performing agents to improve ratings
- Optimize staffing during peak hours
- Reduce failed and incomplete calls
- Improve customer retention strategies

---

## ⚠️ Risks & Mitigation
| Risk | Mitigation |
|------|-----------|
| Over-hiring | Monitor calls per agent |
| Ineffective training | Track rating improvements |
| High tech cost | ROI-based implementation |

---

## 🛠️ Tools Used
- Microsoft Excel
  - Pivot Tables
  - Charts (Line, Bar, Column, Pie, Donut, Scatter)
  - Slicers
  - Data Cleaning Functions

---

## 📊 Dashboard Preview
<img width="1483" height="548" alt="Astrosage AnalysisDashboard" src="https://github.com/user-attachments/assets/bc487fba-e7a9-4628-86b7-3721c1327a8d" />


---

## 🧠 Conclusion
This dashboard provides a **comprehensive view of call center performance**, enabling data-driven decisions to enhance efficiency, improve customer satisfaction, and maximize profitability.

---

## 🚀 Future Enhancements
- Integration with Power BI
- Real-time data tracking
- Predictive analytics using machine learning

## ⭐ If you like this project
Give it a ⭐ on GitHub and share your feedback!
