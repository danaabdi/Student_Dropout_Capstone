# 🎓 UWT Student Dropout Prediction Model

## 📌 Project Overview

This capstone project, developed in partnership with the **University of Washington Tacoma Institutional Research (UWT IR)** team, focuses on identifying and reducing student dropout rates. Using historical academic and demographic data, we built a predictive model to flag at-risk students and support proactive intervention strategies.

## 🧠 Project Objective

- Predict student dropout risk based on academic, demographic, and financial indicators
- Empower advisors and administrators with tools to act before a student drops out
- Enable long-term retention strategy development using data insights

---

## 🧪 Analytics Framework

We followed Microsoft’s **Agile Analytics Lifecycle**:

### Phase 1: Discovery
- Analyzed dropout patterns by Pell Grant eligibility, cohort type, and major
- Discovered spikes in dropout among COVID-19-era cohorts

### Phase 2: Descriptive & Diagnostic Analytics
- Used Power BI to visualize relationships between GPA, age, transfer status, and dropout
- Found students with no prior college exposure were at higher risk

### Phase 3: Predictive Modeling
- Developed a logistic regression model in Azure ML Studio
- Identified key predictors: GPA, time to degree, degree status, transfer status, credits earned
- Delivered probability scores of dropout for each student

### Phase 4: Evaluation & Deployment
- Integrated predictions into **Power Apps** with UI for advisors
- Enabled intervention workflows via **Power Automate**

---

## 🔍 Key Insights

- Dropout rates were **higher (10%) among non-Pell-eligible students** compared to Pell recipients (7.2%)
- **Running Start and College Preparatory students** faced dropout rates as high as **25%**
- Lack of higher-ed experience significantly increased risk of attrition
- Students from **high-demand majors** showed stronger persistence

---

## 🧰 Tools & Technologies

- **Azure ML Studio** – Model training and evaluation  
- **Power BI** – Dashboard and visualization  
- **Power Apps** – Advisor-facing UI for dropout prediction  
- **Power Automate** – Automation of outreach actions  
- **MS SQL Server, Python, R, Excel** – Data extraction and wrangling

---

## 📦 Deliverables

| File / Asset                    | Description                                           |
|--------------------------------|-------------------------------------------------------|
| ` 593 Data Analysis Plan (4).docx`      | Project plan and analytics roadmap                   |
| `Copy of Team 7 Showcase Oral Consultative Presentation.pdf`| Capstone presentation slides                         |
| `Dropout_analysis_DA (1).ipynb` | Exploratory Data Analysis and ML model   |
| `Predictive Model .png`  | Poster summarizing full project pipeline             |

---

## 👥 Team Members

- Dana Abdirakhym
- Diane Hoang
- Dounia Benjdya  
- Sukhdeep Kaur  
- Justin Cabanos  

**Client:** Joe Lawless, UWT Strategy Officer  
**Advisor:** Alice Few, Institutional Analyst

---

## 🔒 Data Disclaimer

All data used in this project adhered to **FERPA compliance** and **UWT Institutional Research policies**. Personally identifiable information (PII) was handled through secure access protocols within university systems.

---

## 💡 Impact

This model provides a **real-time risk scoring system** to help UWT reduce attrition, improve graduation rates, and support equity goals. It sets a foundation for long-term data-informed retention strategies in higher education.

---
