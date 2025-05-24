# 📊 Retail Promo Campaign Analysis

This project is part of the **Codebasics Virtual Internship Challenge**, focused on performing **exploratory data analysis (EDA)** and generating **actionable business insights** on a retail promotional campaign dataset. It simulates the responsibilities of a data analyst intern working closely with marketing and operations teams.

## 🧾 Objective

Analyze the effectiveness of promotional campaigns in retail, across cities, product categories, and store networks. Measure performance using key KPIs:

* **IR% (Incremental Revenue %)**
* **ISU% (Incremental Sold Units %)**

Deliver both analytical results and a **stakeholder-ready presentation** summarizing key insights and strategic recommendations.

---

## 📁 Dataset Overview

The dataset includes:

* Store information (store ID, city)
* Product data (code, name, category, base price)
* Campaign metadata (ID, name, date range)
* Promotional events (promo type, base prices before/after promo, quantity sold before/after)

---

## 🔍 Key Questions Addressed

1. Distribution of stores by city
2. Category-wise contribution to Sankranti sales (after promo)
3. Correlation between post-promo base price and units sold
4. Pre-promo quantity distribution across categories
5. ISU% comparison across cities
6. IR% vs ISU% for promo types in Hyderabad
7. Revenue before vs after promotions in Bengaluru
8. Top product by IR% during Sankranti
9. Lowest ISU% store in Visakhapatnam (Diwali)
10. Promo type with negative IR% and ISU% in Sankranti

---

## 📈 Visualizations Used

* Bar Chart: Store count per city
* Pie Chart: Category contribution to Sankranti sales
* Heatmap: Correlation between base price and quantity sold
* Histograms: Quantity sold before promotion by category
* Line Chart: ISU% across cities
* Scatter Plot: IR% vs ISU% for promo types
* Bar Chart: Revenue before/after by category in Bengaluru

---

## 🧠 Key Insights

* Grocery & Staples dominate post-promo sales
* High price sensitivity: lower prices correlate with higher sales
* Promotions are more effective in some cities than others (e.g., Hyderabad)
* Essentials respond better to promos than durable goods
* Need to balance IR% and ISU% when evaluating promo success

---

## 📦 Deliverables

* Python notebook for full analysis
* Visuals exported as PNG/SVG
* Google Slides presentation deck with speaker notes
* README documentation (this file)

---

## 🛠 Tools & Libraries

* Python (pandas, matplotlib, seaborn)
* Jupyter Notebook
* PowerPoint / Google Slides

---

## 📌 How to Use

1. Clone this repository
2. Open the notebook: `retail_promo_analysis.ipynb`
3. Run the analysis to generate visuals and summary tables
4. Review insights in the included presentation PDF or `.pptx`

---

## 🧩 Folder Structure

```
├── data/                  # Raw input data files
├── visuals/               # PNG/SVG exports of plots
├── presentation/          # Final deck and script
├── retail_promo_analysis.ipynb  # Main analysis notebook
└── README.md              # Project documentation
```

---

## 🙏 Acknowledgements

Thanks to [Codebasics](https://codebasics.io/) for launching this challenge.
Special thanks to @Dhaval Patel and @Hemanand Vadivel for curating this hands-on experience.

---

## ✍ Author

**Sergey Kravchenko**
Aspiring Data Analyst | Python + Data Viz Enthusiast

Feel free to connect on https://www.linkedin.com/in/sergiy-kravchenko-it-pm/
