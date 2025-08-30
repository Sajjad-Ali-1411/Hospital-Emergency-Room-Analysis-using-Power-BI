# Hospital-Emergency-Room-Analysis-using-Power-BI
Healthcare analytics project using Power BI to improve Emergency Room productivity by reducing wait times, optimizing staff allocation, and enhancing patient outcomes.
# 🏥 Hospital Emergency Room Analysis

## 📌 Project Overview
This project analyzes **Emergency Room (ER) productivity** using hospital data visualized in **Power BI**.  
The goal is to identify bottlenecks, optimize resource allocation, and provide **actionable recommendations** to hospital management.

---

## 🎯 Objectives
- Understand patient flow (peak hours, day-of-week patterns, demographics).
- Analyze the average satisfaction score of patients on a daily basis to evaluate the quality of service provided.
- Calculate the average time patients wait before being attended to by a medical professional.
- Study **bed occupancy & diagnostics turnaround** to improve efficiency.
- Offer granular insights into patient-level data to enable detailed analysis and troubleshooting.
- Monitor key metrics and trends on a month-by-month basis to identify patterns and areas for improvement.
- Provide stakeholders with insights to **reduce ER congestion, improve care quality, and increase productivity**.

---

## 📸 Dashboard Preview

# Consolidate View
<img width="1293" height="728" alt="Consolidate view" src="https://github.com/user-attachments/assets/bb137cea-91de-434e-8d24-0e172d711e5b" />


# Monthly View
<img width="1291" height="731" alt="Monthly view" src="https://github.com/user-attachments/assets/11b7b747-1457-409f-880d-af3ae0548fd5" />


# Quarterly View
<img width="1294" height="729" alt="Quaterly view" src="https://github.com/user-attachments/assets/5d8e2c8d-b75c-40ef-9d55-79a65acfca57" />


# Patient Details
<img width="1290" height="729" alt="Pateint details" src="https://github.com/user-attachments/assets/2a295e6e-4448-4699-9d1b-e0e3f6b862db" />

---

## 📊 Tools & Technologies
- **Power BI** → Dashboard & visualization  
- **SQL (PostgreSQL)** → Data extraction & transformation   
- **Excel/CSV** → Data export/import  

---

## 🔍 Key Insights
1. ER visits peak between **5 PM – 11 PM** → staffing should be increased during this period.
2. Average waiting time is significantly higher, approximately 35.3 min. The average satisfaction score is 4.99 out of 10, which is low and needs improvement.
3. **Waiting time > treatment time**, meaning bottlenecks are at **triage/registration** not clinical care.  
4. Majority of Patients are aged 20–40 years; a notable share of children (0–10) and seniors (65+).
5. A significant number of patients (5400) did not require referrals. Most commonly, referrals are from General Practice (1840), followed by Orthopedics (995). 
6. Most patients are **discharged**, suggesting urgent-care clinics could handle many.  
7. High **repeat visits** indicate poor follow-up care and discharge communication.  
8. **Lab & imaging delays** are a major contributor to overall patient length of stay.  

---

## 📈 Recommendations
- Adopt **dynamic staffing** based on demand heatmaps (hour & day-of-week).  
- Introduce a **Fast-Track zone** for low-severity cases.  
- Implement **digital check-in & AI triage** to reduce waiting times.  
- Launch **post-discharge follow-up programs** (SMS/phone calls).  
- Strengthen **urgent-care partnerships** to divert non-critical cases.  
- Track **KPIs**: wait time, occupancy rate, repeat visits, diagnostics turnaround.  

---

## 📂 Repository Contents
- `dashboard/Hospital.pbix` → Power BI dashboard  
- `reports/Hospital_ER_Executive_Summary.pdf` → One-page summary for stakeholders  
- `visuals/` → Exported dashboard screenshots for quick view  

---

## 📌 How to Use
1. Download the `Hospital.pbix` file and open it in **Power BI Desktop**.  
2. Explore interactive visuals for patient flow, bed utilization, and repeat visits.  
3. Refer to `reports/` for ready-to-share stakeholder documents.  

---

## 🙌 Acknowledgments
This is a sample project built for **healthcare analytics portfolio** purposes.  
No real patient-identifiable data is included.
