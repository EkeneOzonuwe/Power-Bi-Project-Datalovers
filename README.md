# 🏨 Hotel Booking Analytics — Power BI Dashboard

An end-to-end Power BI project analysing hotel booking data to uncover revenue trends, booking patterns, and guest behaviour insights for a hotel chain client.

---

## 📊 Final Dashboard

<img width="1487" height="959" alt="image" src="https://github.com/user-attachments/assets/96a6a889-fd4d-40ec-9142-1590f1565943" />

---

## 🔑 Key Metrics

| Metric | Value |
|--------|-------|
| Total Revenue | $39.36M |
| Total Bookings | 101K |
| Total ADR (Avg Daily Rate) | $10.52M |
| Booking Ratio (City : Resort) | 4:1 |
| Average Length of Stay | 4 nights |

---

## 💡 Key Insights

- **City Hotels dominate** — accounting for 52.18% of total revenue ($20.54M) vs Resort Hotels at 47.82% ($18.82M)
- **Peak season is Q3** — the third quarter had the highest Total ADR, indicating summer is the busiest and most profitable period
- **Lead time peaks in July/August** — guests book furthest in advance for summer arrivals
- **Portugal is the top booking country** — followed by the UK, France, Spain, and Germany
- **No deposit bookings are most common** — an opportunity to incentivise advance deposits to reduce cancellations
- **Average ADR peaks mid-year** — rising from ~$75 in January to over $150 in August before declining

---

## 🎯 Problem Statement

A prominent hotel chain engaged Datafied Technologies to leverage data analytics for insights into booking patterns, guest demographics, and operational efficiencies — with the goal of enhancing customer satisfaction and optimising revenue.

---

## 📁 Data Sourcing

- **Source:** [Kaggle — Hotel Booking Dataset](https://www.kaggle.com/)
- **Power BI File:** [Download Dashboard on Google Drive](https://drive.google.com/file/d/1gYg33c6ZDvbBa4Tao5DtiKULji-Jk2Q_/view?usp=drive_link)

---

## 🔧 Data Transformation & Cleaning

The dataset was cleaned by:
- Removing duplicates and white spaces
- Correcting data type inconsistencies
- Formatting columns for analysis and visualisation

**Original Data**
<img width="1446" height="834" alt="image" src="https://github.com/user-attachments/assets/46b7413b-71c8-4a16-ac9e-fa6b226a0264" />

**Transformed Data**
<img width="1457" height="829" alt="image" src="https://github.com/user-attachments/assets/ce52c27e-8ee3-40f2-a5cc-d7c706098d7e" />

---

## 🗄️ Data Modeling

To further break down the data, the following dimension tables were created:

- Market Table
- Hotel Table
- Date Table
- Meal Table
- Location Table

The data model was designed using a **Star Schema** where all dimension tables connect to the Facts table in a one-to-many relationship.

<img width="1711" height="773" alt="image" src="https://github.com/user-attachments/assets/b4c0da6e-5af4-41a5-b329-2e4384d6b9c3" />

---

## 🛠️ Tools Used

- **Power BI** — data modelling, DAX measures, dashboard design
- **Power Query** — data transformation and cleaning
- **DAX** — calculated measures (ADR, Total Revenue, Ratios)
- **Kaggle** — data source

---

*Project completed as part of a guided Power BI analytics course.*
