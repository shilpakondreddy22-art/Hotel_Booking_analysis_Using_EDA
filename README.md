# 🏨 Hotel Booking Data Analysis (EDA Project)

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](#)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](#)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-orange.svg)](#)
[![Made with ❤️](https://img.shields.io/badge/Made%20with-❤️%20by%20Shilpa%20Reddy-pink.svg)](#)

---

## 🔍 Overview
An end-to-end **Exploratory Data Analysis (EDA)** project on hotel booking data to understand **customer behavior**, **cancellations**, **pricing patterns**, and **seasonal demand**.  
The project compares **City Hotels** and **Resort Hotels**, delivering insights that help improve revenue, occupancy, and guest satisfaction.

**Dataset:** 119,390 rows × 36 columns  
**Goal:** Extract actionable insights to reduce cancellations and improve hotel performance.

---

## 🎯 Objectives
- 📊 Compare **City vs Resort Hotel** booking patterns  
- 🔍 Identify **key drivers of cancellations** (lead time, deposit type, channel)  
- 💰 Analyze **Average Daily Rate (ADR)** and seasonality  
- 💡 Provide **data-driven recommendations** for smarter business strategy  

---

## 🧹 Data Cleaning & Preparation
- 🧩 Filled missing values (`children`, `country`, `agent`, `company`)  
- ✂️ Treated outliers in `adr` and `lead_time` using IQR method  
- 🕒 Converted `reservation_status_date` to datetime  
- 🔠 Standardized categorical values and text formats  
- ✅ Removed duplicates and ensured data consistency  

---

## 📊 Key Insights
- 🏙️ **City Hotels** record more bookings but have lower ADR than **Resort Hotels**  
- ⏳ **Long lead times** and **No Deposit** bookings lead to higher cancellation rates  
- 🌐 **OTAs (Online Travel Agents)** generate large volume but more cancellations  
- 🔁 **Repeat guests** are loyal and yield higher ADR  

---

## 💡 Recommendations
1. 💵 Introduce **partial prepayment** for long lead-time bookings  
2. 📈 Apply **dynamic pricing** based on seasonality and demand  
3. 💻 Encourage **direct bookings** to reduce OTA dependency  
4. 🎁 Strengthen **loyalty programs** for repeat guests  

---

## 🛠️ Tools & Libraries
- 🐍 **Python**  
- 📦 **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn  
- 💻 **Environment:** Jupyter Notebook  
- 📊 **Visualization:** PowerPoint  

---
## 📂 Repository Structure

├── data/
│   └── hotel_booking.csv
│
├── notebooks/
│   ├── 01_EDA_PHASE_1.ipynb  # Data Cleaning & Univariate Analysis
│   └── 02_EDA_PHASE_2.ipynb  # Bivariate, Multivariate & Trend Analysis
│
├── presentations/
│   └── EDA-PHASE-1&2-HOTEL_BOOKINGS.pptx  # Final PPT Presentation
│
├── reports/
│   ├── EDA-PROJECT-PHASE-1.zip  # Phase 1 EDA Report Files
│   └── EDA-PROJECT-PHASE-2.zip  # Phase 2 EDA Report Files
│
├── requirements.txt   # Python Dependencies
└── README.md          # Project Documentation




--- 
## 💬 Final Note
✨ Transforming hotel booking data into **valuable insights** for smarter business decisions.  
> *“Data turns confusion into clarity and decisions into success.”* 🚀

