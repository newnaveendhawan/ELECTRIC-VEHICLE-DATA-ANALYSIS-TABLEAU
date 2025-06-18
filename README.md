# 🚘 Electric Vehicle Data Analysis Dashboard

![ELECTRIC VEHICLE DATA ANALYSIS](https://github.com/user-attachments/assets/8cabbced-6c87-4cd9-ac68-743c9938a8ab)

This project presents a Tableau dashboard to analyse electric vehicle (EV) adoption trends based on real-world data. It offers a breakdown by vehicle type, make, model, state, year, and eligibility under the Clean Air Vehicle (CAFV) program. The dashboard is focused on electric vehicle registrations in the U.S., with a strong emphasis on data from **Washington State**.

---

## 📚 Table of Contents

- [🔍 Project Overview](#-project-overview)
- [📌 Key Insights from the Dashboard](#-key-insights-from-the-dashboard)
- [📊 Dashboard Features](#-dashboard-features)
- [🔧 Tools & Technologies Used](#-tools--technologies-used)
- [🧠 Suggestions for Next Steps](#-suggestions-for-next-steps)
- [📁 Project Structure](#-project-structure)
- [🌐 Glimpse of Dashboard](#-glimpse-of-Dashboard)
- [📥 Data Source](#-data-source)
- [📃 License](#-license)
- [🙋‍♂️ Author](#-about-the-author)

---

## 🔍 Project Overview

The **Electric Vehicle Data Analysis Dashboard** is an interactive Tableau project that explores electric vehicle (EV) adoption trends across the United States, with a strong focus on **Washington State**. Using a dataset of over **150,000 EV records**, this dashboard provides insights by:

- EV Type (BEV vs PHEV)
- Make and Model
- Model Year
- State Distribution
- CAFV (Clean Air Vehicle) Eligibility

The dashboard is designed to help **policy makers, analysts, and sustainability advocates** understand how EV usage is growing over time, which manufacturers and models lead the market, and where improvements are needed in data quality and infrastructure.

Key objectives:
- Track growth in EV adoption by year and model
- Identify top-performing manufacturers and models
- Highlight state-wise EV concentration
- Analyze CAFV eligibility and missing data

## 📌 Key Insights from the Dashboard

### 🔹 Overall Statistics
- **Total EVs Analysed:** 150,413
- **Average Electric Range:** 67.83 miles
- **EV Types:**
  - **BEV (Battery Electric Vehicles):** 116,745 (77.6%)
  - **PHEV (Plug-in Hybrid Electric Vehicles):** 33,668 (22.4%)

### 🔹 Year-wise EV Adoption Trends
- Consistent growth from **2011 to 2017**.
- Rapid rise from **2018 to 2023**, peaking in **2023** with **37,100 vehicles**.
- Sharp drop in 2024 (only **600 vehicles**) likely due to incomplete data for the year.

### 🔹 Most Popular Makes
- **Tesla** leads the market with **68,939 vehicles** (48.15% of total).
- Other top manufacturers include:
  - Nissan
  - Chevrolet
  - Ford
  - BMW
  - Kia

### 🔹 Top Models
| Model       | Make     | Type | Vehicles | % of Total |
|-------------|----------|------|----------|-------------|
| Model Y     | Tesla    | BEV  | 28,501   | 18.95%      |
| Model 3     | Tesla    | BEV  | 27,708   | 18.42%      |
| Leaf        | Nissan   | BEV  | 13,187   | 8.77%       |
| Model S     | Tesla    | BEV  | 7,609    | 5.06%       |
| Bolt EV     | Chevrolet| BEV  | 5,732    | 3.81%       |

### 🔹 State-wise Distribution (Corrected)
- **Washington (WA)** alone accounts for **150,082 out of 150,413 vehicles**, showing a strong geographical concentration.
- Most other U.S. states report 1–12 vehicles, indicating the dataset is either **exclusive to Washington** or **incomplete for other regions**.

### 🔹 CAFV Eligibility Breakdown
- **Eligible:** 62,887 (41.81%)
- **Not Eligible:** 17,829 (11.85%)
- **Unknown:** 69,697 (46.34%) – a significant portion has missing eligibility data.

---

## 📊 Dashboard Features

- **Interactive Filters:** CAFV eligibility, EV type, make, model, and state
- **Visuals Include:**
  - Year-wise vehicle trend (line chart)
  - State-wise map visualisation
  - Top 15 vehicle makes (bar chart)
  - Top 10 vehicle models (table with %)
  - CAFV eligibility breakdown (donut chart)

---

## 🔧 Tools & Technologies Used

- **Tableau Public / Desktop** – For creating the dashboard
- **Excel / CSV** – Raw dataset format
- **Mapbox (via Tableau)** – State-wise geospatial visualization

---

## 🧠 Suggestions for Next Steps

1. **Expand Beyond Washington** – Integrate more states for a comprehensive national analysis.
2. **EV Range Comparison** – Analyse how electric range varies by model/year.
3. **Charging Infrastructure** – Overlay EV adoption with public charging availability.
4. **Policy Impact Study** – Compare EV growth vs. state/federal EV incentives.
5. **Forecast Future Trends** – Use time series models (ARIMA/SARIMA) to forecast EV adoption till 2030.
6. **Clean Missing Fields** – Especially CAFV eligibility and vehicle range.

---

## 📁 Project Structure

##### 📁 electric-vehicle-dashboard/
###### └── 📁 Images/
######     └── 📁 Main Dashboard image/
######         ├── 📊 ELECTRIC VEHICLE DATA ANALYSIS TABLEAU DASHBOARD IMAGE.png
###### └── 📁 Tableau Workbook/
######     ├── 📄 ELECTRIC VEHICLE DATA ANALYSIS TABLEAU DASHBOARD.twbx
###### ├── 📄 README.md
###### └── 📁 data/
######     └── electric_vehicle_data.csv (not included, link below)


## 🌐 Glimpse of Dashboard
![ELECTRIC VEHICLE DATA ANALYSIS TABLEAU DASHBOARD IMAGE](https://github.com/user-attachments/assets/2932cb77-a713-4283-9efe-6a62a9a36e6c)
---

## 📥 Data Source

> The dataset is not included due to size limits.  
> You can download from the [Google Drive](https://drive.google.com/file/d/1Df33DQ1X1vaEMGY4CzKelltNTWo2XV50/view?usp=drive_link)   
> Original Dataset of this project [click here](https://drive.google.com/file/d/1Df33DQ1X1vaEMGY4CzKelltNTWo2XV50/view?usp=drive_link)
> Download Tableau Public [from here](https://drive.google.com/file/d/16briz2kzEzgqji0fjVeRH51fJwvLo4lP/view?usp=drive_link)
---

## 📃 License

This project is released under the [MIT License](https://github.com/newnaveendhawan/ELECTRIC-VEHICLE-DATA-ANALYSIS-TABLEAU/blob/main/LICENSE).

---

## 👨‍💻 About the Author
### Naveen Dhawan
###### 📧 newnaveendhawan@gmail.com
###### [💼 LinkedIn](https://www.linkedin.com/in/newnaveendhawan/) 
###### [📁 Portfolio](https://naveendhawanportfolio.blogspot.com/) 
###### 🎓 BTech – NIT Warangal | Data Analyst | ML Enthusiast | Power BI & Python
