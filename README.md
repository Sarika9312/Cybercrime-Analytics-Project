🔍 Cybercrime Analytics – End-to-End Data Analytics Project

A complete real-world cybercrime analytics project using Python, MongoDB & Tableau, built to analyze how cybercrimes spread across India based on fraud type, state, gender, age, and financial impact.

This project answers real-world questions like:

🔹 Which types of cybercrimes are most common in India?

🔹 Which states report the highest incidents?

🔹 Which gender is more affected?

🔹 How much financial loss does each scam type cause?

🔹 Are there any seasonal/monthly trends in crime reports?

The goal:
Convert raw cybercrime data → insights → interactive Tableau dashboard.

🗂️ Project Structure
Cybercrime-Analytics-Project/
│

├── cybercrime_data.csv              # Final dataset used in Tableau

│

├── dashboard/

│   └── CyberCrime_Dashboard.twbx    # Tableau Dashboard (packaged workbook)

│

└── README.md

🛠️ Tech Stack Used

📌 Data Handling & Processing

Python

Pandas

NumPy

📌 Database (Optional Step)

MongoDB

MongoDB Compass

📌 Visualization

Tableau Public

Interactive charts, maps & dashboards

📊 Dashboard Highlights

1️⃣ Crime Type Distribution

Bar chart showing which cyber fraud types are most common

Helps identify rising scams like UPI fraud, loan scam, phishing

2️⃣ Loss by Type

Visual comparison of financial losses caused by different scam categories

3️⃣ Age Distribution

Histogram to analyze which age groups are most affected

4️⃣ State-wise Crime Map

Filled map of India showing state-wise incident density

Darker states → more cybercrime cases

5️⃣ Gender-wise Victims

Pie chart showing distribution of complaints by gender

6️⃣ Monthly Trend Analysis

Seasonal patterns in cybercrime reporting

🧹 Data Cleaning & Preparation

Performed in Python:

Removed duplicates & missing values

Standardized state names

Converted dates → usable datetime format

Added random geo-coordinates (latitude, longitude) for map visualization

Encoded categorical fields

🚀 How to Run the Project

1️⃣ Download Project Files

Clone or download:

git clone https://github.com/Sarika9312/Cybercrime-Analytics-Project.git

2️⃣ Open Tableau Dashboard

File → Open →
dashboard/CyberCrime_Dashboard.twbx

Dashboard will load automatically.

3️⃣ (Optional) Import Data into MongoDB

If you want to recreate the Python → MongoDB workflow:

mongoimport --db cybercrime_db --collection complaints --file cybercrime_data.csv --type csv --headerline

🎯 Key Insights (TL;DR)

📌 UPI Fraud, Job Scam & Phishing are the most reported cybercrimes.

📌 Financial losses are highest in Loan Scam & Credit Card Fraud.

📌 Maharashtra, UP, Karnataka report the highest cases.

📌 25–40 age group is most impacted.

📌 Crimes increase in certain months due to seasonal activity.

👩‍💻 Author

Sarika Panchalwar

Engineering Student | Data Analyst (Beginner → Pro)

📍 India

🌐 GitHub: https://github.com/Sarika9312

💫 If you like this dashboard

⭐ Star the repo — it motivates me to build more awesome projects!
