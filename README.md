# Superstore Sales Analysis Dashboard (Tableau)

## Project Overview

An end-to-end **sales analysis dashboard** built with **Tableau Desktop** and **Tableau Prep Builder** on the Superstore retail dataset. The main challenge — and focus — of this project was **cleaning and unifying messy regional order data** that arrived in different file formats and column layouts, then turning it into a single interactive dashboard for analysing sales, profit, and returns.

---

## Business Objective

The dashboard helps answer key retail questions such as:

- Which regions and states generate the most sales and profit?
- Which product categories and sub-categories are most / least profitable?
- How do the different customer segments (Consumer, Corporate, Home Office) compare?
- Where are discounts eroding profit?
- Which orders are being returned, and why?

---

## The Data Challenge

The raw order data was intentionally messy and came in **several inconsistent formats**, which is the core of this project:

- **Central region** — single flat file, one column layout
- **West region** — a pre-joined file with duplicated `Right_` columns that needed cleaning
- **South region** — split across four separate yearly files (2015–2018) with columns in a different order
- **Returns** — separate returns and return-reasons files to be joined back in

All of these were combined, cleaned, and standardised in **Tableau Prep Builder** before analysis.

---

## Tools Used

- Tableau Desktop
- Tableau Prep Builder
- Microsoft Excel / CSV
- Git & GitHub

---

## Workflow

```
Messy regional order files (Central / East / West / South by year)
        ↓
Tableau Prep Builder
(clean · standardise columns · union regions · join returns)
        ↓
Unified sales dataset
        ↓
Tableau Desktop
        ↓
Interactive Sales Dashboard
```

---

## Dashboard Features

- Sales and profit overview by region and state
- Category and sub-category performance
- Customer segment comparison
- Discount vs. profit analysis
- Returns analysis by reason

---

## Repository Structure

```
orders_tableau/
├── data/
│   ├── Orders_Central.csv
│   ├── Orders_East.xlsx
│   ├── Orders_West.csv
│   ├── orders_south_2015.csv
│   ├── orders_south_2016.csv
│   ├── orders_south_2017.csv
│   ├── orders_south_2018.csv
│   ├── Orders_Return_Superstore.xlsx
│   └── return_reasons_new.xlsx
│
├── dashboard.twb/
│   ├── dashboards-20.twb          # Tableau workbook
│   └── orders.prep.tfl            # Tableau Prep flow
│
└── README.md
```

---

## How to Use

1. Clone this repository:

```bash
git clone https://github.com/Harshitharam25/orders_tableau.git
```

2. Open `dashboard.twb/orders.prep.tfl` in **Tableau Prep Builder** to see the data-cleaning flow.
3. Open `dashboard.twb/dashboards-20.twb` in **Tableau Desktop** to explore the dashboard.
4. If prompted, reconnect the workbook to the files in the `data/` folder.

---

## Future Enhancements

- Publish the dashboard to **Tableau Public** so it can be viewed live in a browser
- Add screenshots of the dashboard to this repository
- Add drill-down navigation and dashboard actions

---

## Author

**Harshitha Ram**

MSc Data Science & Business Analytics — EDC Paris Business School

- GitHub: [@Harshitharam25](https://github.com/Harshitharam25)
- LinkedIn: [harshitharam-linkcode1](https://www.linkedin.com/in/harshitharam-linkcode1/)
