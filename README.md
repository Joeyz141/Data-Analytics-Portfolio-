# Software Engineering & Data Analytics Portfolio

### Tools & Technologies

**Software Engineering:** PHP • JavaScript • SQL (MySQL / MariaDB) • REST-style JSON APIs • HTML • CSS  
**Data & Analytics:** Python • Pandas • NumPy • Scikit-learn • Plotly • Streamlit • Matplotlib • Power BI • Excel  
**DevOps & Testing:** Docker • AWS (EC2) • PHPUnit • pytest • Git & GitHub  
**AI-Assisted Development:** Claude / Claude Code

This repository highlights selected software engineering, data analytics and machine learning projects. They range from a full-stack web application deployed on AWS to predictive models, web scraping and business dashboards.

Each project focuses on solving a real-world style problem end to end: designing the data, building the tool or model, testing it, and turning the results into something people can use.

---

## Projects

### Maintenance Request Dashboard (Full-Stack Web App, Live on AWS)
An internal tool for a vehicle maintenance team to create, view, search, filter and update maintenance requests, with a JSON API and a Python analytics dashboard. Built with Claude as an AI development assistant, with a focus on understanding and explaining every part of the architecture, code, testing and deployment.

Key Features:
- PHP + MySQL app with validated forms, prepared statements, XSS escaping and CSRF protection
- Live search and filtering with JavaScript `fetch()` (still works with JavaScript turned off)
- JSON API used by both the front end and a Streamlit + Plotly analytics dashboard
- 47 automated tests (PHPUnit + pytest), including contract tests that keep the code in sync with the database schema
- Deployed with Docker Compose on AWS EC2 with HTTPS (Caddy + Let's Encrypt)

Tools Used:
PHP, MySQL (MariaDB), JavaScript, Python (Pandas, Plotly, Streamlit), PHPUnit, pytest, Docker, AWS EC2, Git & GitHub, Claude

Live Demo:
https://32-190-224-231.sslip.io

Repository:
https://github.com/Joeyz141/Maintenance-Request-Dashboard

---

### Coffee Shop Sales Analysis
Exploratory analysis of coffee shop sales data to identify revenue drivers, customer purchasing patterns, and sales trends.

Focus Areas:
Sales trends, product performance, business insights

Tools Used:
Excel, Power BI, Data Visualization

Repository:
https://github.com/Joeyz141/Coffee-Shop-Sales-Analysis-.git

---

### Financial Fraud Detection Analysis
Built a fraud detection model using transaction behavior and risk indicators.

Key Result: **Logistic Regression model achieving ~0.97 ROC-AUC**

Tools Used:
Python, Pandas, Scikit-learn, Matplotlib

Repository:
https://github.com/Joeyz141/Financial_Fraud-.git

---

### EOPS Program Impact Analysis (Thesis Project)
Web-scraped institutional data and built regression models to analyze the impact of student support programs on academic outcomes.

Focus Areas:
Student success metrics, program effectiveness

Tools Used:
Python, Web Scraping, Pandas, Scikit-learn, Matplotlib

Repository:
https://github.com/Joeyz141/EOPS_WebScrape_RegressionModel

---

### Spotify Customer Churn Analysis
Analyzed customer listening behavior to identify factors contributing to user churn and built a predictive churn model.

Focus Areas:
Customer engagement patterns, churn prediction, user behavior analysis

Tools Used:
Python, Pandas, Scikit-learn, Matplotlib

Repository:
https://github.com/Joeyz141/Spotify2025_Analysis

---
## Skills Demonstrated

**Software Engineering**  
• Full-stack web development (PHP, JavaScript, SQL)  
• Relational database design (primary/foreign keys, constraints)  
• API design and frontend/backend communication  
• Web security basics (prepared statements, XSS escaping, CSRF tokens, least-privilege database users)  
• Automated testing and debugging (PHPUnit, pytest)  
• Containerization and cloud deployment (Docker, AWS EC2, HTTPS)  
• Git workflow with branches and pull requests  
• AI-assisted development with Claude, verified through testing and code review  

**Data Analytics**  
• Data Cleaning & Data Preparation  
• Exploratory Data Analysis (EDA)  
• Predictive Modeling & Machine Learning  
• Data Visualization & Dashboarding  
• Web Scraping & Data Collection  
• Business Insight & Data-Driven Recommendations  

---
## About

These projects demonstrate both software engineering and applied data analytics. The Maintenance Request Dashboard shows building, testing and deploying a full-stack application. The analytics projects cover fraud detection, customer behavior, sales performance and educational program impact.
