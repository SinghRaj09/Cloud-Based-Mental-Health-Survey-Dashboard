# 🧠 Cloud Based Mental Health Survey Dashboard

## 📘 Overview
**Cloud-Based Mental Health Survey Dashboard** is an end-to-end, cloud-enabled system to **collect, analyze, and visualize** student mental health data in real time. The system uses **Google Forms** for anonymous data collection, **Google Sheets** as a live datastore, **Python** for data cleaning and analysis, and **Power BI** for interactive dashboards. The project was developed as an undergraduate engineering project and evaluated on a pilot dataset (≈210 responses).

## ⚙️ Key Features
- ✅ **Anonymous survey collection** (PHQ-9, GAD-7, PSS-10 based questions)
- ☁️ **Cloud integration**: Google Forms → Google Sheets (live)
- 🧮 Data cleaning & statistical analysis with Python (pandas, NumPy, matplotlib)
- 📊 Interactive Power BI dashboard with slicers, heatmaps, and trend lines
- 🔔 Rule-based recommendations (threshold alerts for high risk)
- ♻️ **Automated refresh**: dashboard updates via Sheets (5-minute refresh target)

## 🛠 Tech Stack

- Survey / Storage: Google Forms → Google Sheets. 
- Data cleaning & analysis: Python (pandas, NumPy, matplotlib). 
- Visualization / Dashboard: Microsoft Power BI (interactive .pbix). 
- Excel for intermediate cleaning, GitHub for version control.

## 🧪 What we measured / key findings

- Pilot survey collected ~210 responses with validated scales and demographic fields. 
- Strong positive correlations observed between stress and anxiety (example r ≈ 0.74) and anxiety–depression (r ≈ 0.77). Negative correlation observed between sleep hours and stress.

## ✅ Best practices & ethics

- Keep all responses anonymous (no PII).
- Require explicit consent checkbox in the form.
- Store sensitive data off the public repo and share only anonymized examples.
- Include an IRB / supervisor approval note if required by your institution.

## 🔭 Future enhancements

- Web-based front-end to replace Google Forms (Flask / Node.js).
- Automate backend processing with scheduled Cloud Functions or a small Flask API.
- Add ML-based predictive model for early warning (risk scoring).
- Mobile-friendly dashboards or embedded Power BI for web. 
