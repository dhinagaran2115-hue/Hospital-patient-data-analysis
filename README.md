# 🏥 Hospital Patient Dashboard

## 📊 Healthcare Analytics & Patient Intelligence

An interactive **Power BI Hospital Patient Dashboard** designed to analyze patient admissions, billing, insurance coverage, patient details, and patient status.

---

## 📌 Project Overview

The Hospital Patient Dashboard provides an interactive view of hospital operations and patient information.

The dashboard helps analyze:

- Patient admissions
- Department-wise admissions
- Monthly admission trends
- Admission types
- Patient billing
- Treatment costs
- Room charges
- Medicine costs
- Laboratory costs
- Doctor charges
- Insurance coverage
- Insurance providers
- Patient details
- Patient length of stay
- Patient status

---

## 🖼️ Dashboard Preview

### 🏠 Home / Overview

![Hospital Dashboard Home](assets/home.png.png)

### 🏥 Admissions Details

![Admissions Dashboard](assets/admissions.png.png)

### 💰 Patient Billing Details

![Billing Dashboard](assets/billing.png.png)

### 👤 Patient Details

![Patient Details](assets/details.png.png)

### 🛡️ Insurance Details

![Insurance Dashboard](assets/insurance.png.png)

### ❤️ Patient Status

![Patient Status Dashboard](assets/status.png.png)

---

# 🎯 Project Objectives

The main objectives of this project are:

1. Analyze total hospital patients.
2. Analyze department-wise admissions.
3. Track monthly admission trends.
4. Analyze scheduled, emergency and referral admissions.
5. Analyze total hospital billing.
6. Analyze treatment, room, medicine, lab and doctor charges.
7. Analyze patient insurance coverage.
8. Compare insurance providers.
9. View detailed patient information.
10. Analyze patient length of stay.
11. Analyze discharged, admitted and referred patients.

---

# 🧰 Tools & Technologies

- **Power BI**
- **Power Query**
- **DAX**
- **Microsoft Excel**
- **Data Visualization**
- **Data Analysis**

---

# 📊 Dashboard Pages

## 1. 🏠 Home / Overview

The Home page provides a high-level overview of hospital performance.

### Key KPIs

| KPI | Value |
|---|---:|
| 👥 Total Patients | 2K |
| 💰 Total Billing | 131M |
| 👨‍⚕️ Total Doctors | 30 |

---

## 2. 🏥 Admissions Details

The Admissions page analyzes patient admission patterns.

### Department-wise Admissions

The dashboard compares admissions across:

- Pediatrics
- Neurology
- Oncology
- Cardiology
- Dermatology
- Gastroenterology
- Orthopedics
- ENT
- General Medicine
- Gynecology

### Monthly Patient Admissions

A line chart is used to analyze patient admissions by month.

### Admission Types

Admission types include:

- Scheduled
- Emergency
- Referral

---

## 3. 💰 Patient Billing Details

The Billing page provides a breakdown of hospital billing.

### Key Billing KPIs

| Category | Value |
|---|---:|
| Total Billing | 131M |
| Average Billing | 87.31K |
| Treatment | 62M |
| Room | 36M |
| Medicine | 16M |
| Lab | 11M |
| Doctor | 6M |

The Patient ID slicer allows users to filter billing information for an individual patient.

---

## 4. 👤 Patient Details

The Patient Details page provides detailed patient-level information.

### Patient Information

- Patient ID
- Patient Name
- Age
- Blood Group
- Gender
- City
- Department
- Doctor
- Admission Type

A Patient ID slicer is provided for interactive filtering.

---

## 5. 🛡️ Insurance Details

The Insurance page analyzes patient insurance information.

### Insurance Analysis

The dashboard compares:

- Insured Patients
- Non-Insured Patients

### Insurance Providers

The dashboard includes:

- Self Pay
- Care Health
- Star Health
- Bajaj Allianz
- ICICI Lombard
- New India Assurance
- HDFC ERGO

---

## 6. ❤️ Patient Status

The Patient Status page analyzes patient stay and discharge information.

### Patient Stay Details

The dashboard includes:

- Patient ID
- Admission Year
- Admission Month
- Admission Day
- Length of Stay
- Discharge Year
- Discharge Month
- Discharge Day

### Patient Status

The dashboard analyzes:

- Discharged
- Admitted
- Referred

---

# 📈 Key Visualizations

| Visualization | Purpose |
|---|---|
| KPI Cards | Display important hospital metrics |
| Bar Chart | Department-wise admissions |
| Line Chart | Monthly admission trends |
| Donut Chart | Admission and insurance analysis |
| Table | Patient-level information |
| Slicer | Patient filtering |
| Navigation Buttons | Navigate between dashboard pages |

---

# 🔍 Business Questions

This dashboard helps answer questions such as:

### Patient Analysis

- How many patients are there?
- Which department has the most admissions?
- How many patients are admitted each month?
- What are the different admission types?

### Billing Analysis

- What is the total hospital billing?
- What is the average billing?
- How much is spent on treatment?
- How much is spent on rooms?
- How much is spent on medicines?
- How much is spent on laboratory services?
- How much is spent on doctors?

### Insurance Analysis

- How many patients have insurance?
- How many patients are non-insured?
- Which insurance providers cover patients?

### Patient Status

- How many patients are discharged?
- How many patients are admitted?
- How many patients are referred?
- What is the length of stay?

---

# 🧮 DAX Measures

### Total Patients

DAX
Total Patients =
DISTINCTCOUNT(Patient[Patient ID])

### Total Billing

DAX
Total Billing =
SUM(Patient[Total Billing])

### Average Billing

DAX
Average Billing =
AVERAGE(Patient[Total Billing])

### Total Doctors

DAX
Total Doctors =
DISTINCTCOUNT(Patient[Doctor])


### Total Admissions


DAX
Total Admissions =
COUNTROWS(Patient)

###🔄 Data Analytics Workflow

Hospital Dataset
       ↓
Data Cleaning
       ↓
Power Query
       ↓
Data Transformation
       ↓
Data Modeling
       ↓
DAX Measures
       ↓
Power BI Visualizations
       ↓
Interactive Dashboard
       ↓
Healthcare Insights


### 💡 Key Insights

The dashboard provides insights into:

--Patient admission patterns
--Department workload
--Monthly admission trends
--Admission type distribution
--Hospital billing
--Billing components
--Insurance coverage
--Insurance provider distribution
--Patient demographics
--Length of stay
--Patient status

### 🚀 Future Enhancements

Future versions of the dashboard can include:

--Bed occupancy analysis
--Doctor workload analysis
--Average length of stay by department
--Readmission rate
--Patient satisfaction
--Daily admission and discharge trends
--Revenue by department
--Insurance claim analysis
--Age-group analysis
--Gender-wise admission analysis
--City-wise patient distribution
--Doctor-wise patient analysis



⭐ Final Summary

The Hospital Patient Dashboard is an interactive Power BI healthcare analytics project designed to transform hospital patient data into meaningful and actionable insights. The dashboard provides a comprehensive view of patient admissions, billing, insurance coverage, patient information, length of stay, and patient status.

Using Power BI, Power Query, DAX, and Excel, the project demonstrates the complete data analytics workflow, including data cleaning, transformation, data modeling, KPI creation, and interactive visualization.

The dashboard helps users analyze admission trends, department performance, billing components, insurance distribution, and patient outcomes through interactive charts, KPI cards, slicers, tables, and navigation features.

🛠️ Skills Demonstrated

Power BI | DAX | Power Query | Excel | Data Cleaning | Data Modeling | Data Visualization | Healthcare Analytics

🎯 Project Outcome

This project demonstrates how raw hospital data can be converted into an interactive and user-friendly Business Intelligence dashboard, supporting data-driven analysis and better understanding of hospital operations and financial performance.
