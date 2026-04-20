# 🏥 Hospital KPI Dashboard — Excel

> Interactive healthcare analytics dashboard to monitor patient flow, performance metrics, and operational efficiency.

---

## 📌 Overview

This Excel-based dashboard provides a **comprehensive view of hospital operations and patient analytics** — covering admissions, waiting time, patient satisfaction, demographics, and departmental referrals.

Built using **Pivot Tables, Charts, and Slicers**, this project highlights how Excel can be leveraged for **healthcare KPI monitoring and decision-making**.

**Key focus areas:** Admission analysis · Patient demographics · Waiting time · Satisfaction score · Department referrals · Monthly engagement

---

## 📊 Dashboard Preview

[Dataset & Cleaning Preview](https://github.com/simranmishra01/Hospital-KPI-Dashboard/blob/main/cleaned_data_preview.png)

[Hospital KPI Dashboard](https://github.com/simranmishra01/Hospital-KPI-Dashboard/blob/main/snapshot%20(%20hospital%20KPI%20dashboard%20).png)


---

## 🔢 Top-Line Metrics

| Metric               | Value          | Note                        |
| -------------------- | -------------- | --------------------------- |
| Total Patients       | **9216**       | Overall dataset size        |
| Admission Rate       | **50.04%**     | Balanced admission ratio    |
| Avg Waiting Time     | **35.26 mins** | Key operational KPI         |
| Patient Satisfaction | **4.99 / 10**  | Moderate satisfaction level |

---

## 🛠️ Tech Stack

| Tool                | Role                                |
| ------------------- | ----------------------------------- |
| **Microsoft Excel** | Dashboard development               |
| **Pivot Tables**    | Aggregation and KPI calculation     |
| **Pivot Charts**    | Visualization                       |
| **Slicers**         | Interactive filtering (Year, Month) |
| **Data Cleaning**   | Data preprocessing                  |
| **File Format**     | `.xlsx`                             |

---

## 🚀 Features & Highlights

### Business Problem

Hospitals often struggle with **fragmented data across departments**, making it difficult to track patient flow, waiting times, and satisfaction levels. This leads to inefficiencies in resource allocation and patient experience management.

---

## 📂 Dataset Source

The dataset is a **sample hospital patient dataset** containing admission records, demographics, and operational metrics.

### Key fields include:

* Patient ID
* Admission Date
* Gender
* Age & Age Group
* Race
* Department Referral
* Admission Status
* Waiting Time
* Patient Satisfaction Score

---

## 🎯 Goal of the Dashboard

To build an **interactive KPI dashboard in Excel** that enables:

* Monitoring of patient admissions
* Evaluation of hospital efficiency
* Understanding patient demographics
* Identifying operational bottlenecks

---

## 📊 Key Visuals

| Visual               | Type         | Insight                         |
| -------------------- | ------------ | ------------------------------- |
| Admission Status     | KPI Cards    | Admitted vs Not Admitted split  |
| Patient Age Group    | Bar Chart    | Seniors dominate patient visits |
| Attended Within Time | Donut Chart  | 77% on-time vs 23% delayed      |
| Total Patients       | KPI Card     | Overall patient count           |
| Avg Waiting Time     | Area Chart   | Trend of waiting time           |
| Satisfaction Score   | KPI Card     | Overall experience rating       |
| Gender Analysis      | Pie Chart    | Male vs Female distribution     |
| Department Referral  | Bar Chart    | Most patients have no referral  |
| Monthly Engagement   | Column Chart | Patient activity by month       |
| Filters              | Slicers      | Year and Month                  |

---

## 🎛️ Filters / Slicers Available

* Year (2023, 2024)
* Month (Jan – Dec)

---

## 📈 Department Referral Breakdown

```id="hosp123"
None                █████████████████████████████░░░░░░░░░░░░
General Practice    ███████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
Orthopedics         ███████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
Physiotherapy       ██░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
Neurology           █░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
Others              █░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
```

---

## 💡 Key Business Insights

1. **Admission rate is evenly split (~50%)**
   → Indicates balanced intake but scope for optimizing admission criteria.

2. **77% patients attended on time**
   → Good operational performance, but 23% delay needs improvement.

3. **Average waiting time ~35 minutes**
   → Moderate; reducing this can significantly improve patient satisfaction.

4. **Patient satisfaction score is 4.99/10**
   → Indicates need for service quality improvement.

5. **Majority patients are Seniors**
   → Healthcare services should focus more on elderly care.

6. **Most patients have no department referral**
   → Suggests direct admissions; potential to streamline referral systems.

---

## 🧹 Data Cleaning Steps

* Removed duplicate patient records
* Standardized categorical values (Gender, Department, Race)
* Converted date-time formats
* Handled missing/null values
* Created **Age Group classification**
* Structured dataset for analysis

---

## 🗂️ Project Structure

```id="tree456"
Hospital-KPI-Dashboard-Excel/
│
├── snapshot ( hospital KPI dashboard ).png
├── cleaned_data_preview.png
├── Hospital_KPI_Dashboard.xlsx
└── README.md
```

---

## 🚧 Future Improvements

* Integrate real-time hospital data sources
* Add predictive analytics for patient inflow
* Implement Power BI version for advanced visuals
* Include doctor/department performance KPIs

---

## 🙋‍♀️ Author

**Simran Mishra**
Built using Microsoft Excel

Connect on [LinkedIn](www.linkedin.com/in/simran-mishra-a21368276)

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!

