# 🎓 KJ Somaiya Internship Trends Analysis

An independent data analytics project analysing **2,004 internship records** from K J Somaiya College of Engineering to understand how student internship participation, stipend availability, and seasonal patterns shifted across academic years — with a focus on quantifying the long-term impact of the **COVID-19 pandemic** on student career opportunities.

> 📌 One of the few student-led analytics projects with direct institutional impact — findings were presented to academic stakeholders and used for policy-level decision-making.

---

## 📌 Problem Statement

The COVID-19 pandemic disrupted industries globally, and college students were among the most affected when it came to internship and early career opportunities. But how deep did the impact run — and did the recovery follow? This project uses real institutional data to answer: **How did internship trends at KJSCE change between 2021 and 2024, and what structural gaps exist in stipend availability and seasonal opportunity?**

---

## 📂 Dataset

| Detail | Value |
|---|---|
| Source | K J Somaiya College of Engineering — Internship Records |
| Records | 2,004 internship entries |
| Academic Years | 2021 – 2024 |
| Type | Institutional / Real-world data |

### Key Fields Analysed

| Field | Description |
|---|---|
| Academic Year | Year of internship completion |
| Internship Duration | Length of internship in days |
| Stipend Availability | Whether the internship was paid or unpaid |
| Month / Season | Timing of the internship |
| Domain / Company | Industry and company details |

---

## 🔧 Tech Stack

- **Language:** Python
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`
- **Dashboard:** Power BI
- **Data Source:** Excel / CSV (institutional records)

---

## 🔄 Project Workflow

```
Raw Institutional Data → Cleaning → EDA → Trend Analysis → COVID Impact Analysis → Power BI Dashboard → Stakeholder Presentation
```

### 1. Data Cleaning & Preparation
- Standardised academic year labels and date formats
- Handled missing values in stipend, duration, and domain fields
- Classified internships as paid vs unpaid for stipend gap analysis
- Extracted month and season from internship start dates for seasonal analysis

### 2. Participation Trend Analysis
- Tracked year-over-year internship participation across the 2021–2024 period
- Identified the COVID-19 recovery curve — sharp drop during pandemic years, gradual rebound post-2022
- Compared pre-COVID vs post-COVID participation rates to quantify the disruption

### 3. Stipend Availability Analysis
- Measured the ratio of paid vs unpaid internships across all years
- Identified a **59% decline in paid internships** from 2021 to 2024
- Investigated whether stipend decline correlates with industry sector or company size

### 4. Seasonal Pattern Analysis
- Identified **June–July as the dominant internship season**, accounting for the majority of placements
- Found the **average internship duration to be 61 days**
- Mapped seasonal concentration to understand when students are most and least active

### 5. Power BI Dashboard
Built an interactive dashboard for academic stakeholders covering:
- Year-wise participation trend
- Paid vs unpaid internship split
- Month-wise internship distribution
- Duration distribution across batches
- Domain and sector breakdown

---

## 📊 Key Findings

| Finding | Detail |
|---|---|
| 📉 Paid internship decline | **59% drop** in stipend-bearing internships from 2021–2024 |
| 🗓️ Peak season | **June–July** dominates internship activity |
| ⏱️ Average duration | **61 days** across all recorded internships |
| 🦠 COVID correlation | Post-2020 batches show measurable reduction in both participation and stipend availability |
| 🏢 Stipend gap | A significant share of students are completing internships with no financial compensation |

---

## 💡 Insights & Recommendations Delivered

- **Institutional recommendation:** Proactively engage industry partners in Q1 (Jan–Mar) to build pipelines ahead of the June–July peak season
- **Policy recommendation:** Create a stipend support or reimbursement mechanism for students in unpaid internships, particularly in post-COVID recovery years
- **Student recommendation:** Domains with stronger stipend rates should be highlighted in pre-placement orientation to help students make informed choices

---

## 📁 Repository Structure

```
internship_analysis/
│
├── data/
│   └── final merged.xlsx       # Anonymised institutional dataset
│
├── notebooks/
│   └── internship_eda.ipynb            # Full EDA and trend analysis
│
├── dashboard/
│   └── internship dashboard.pbix       # Power BI dashboard file
│
├── 04_insights.md                      # Key findings and observations
├── 05_recommendations.md              # Policy and institutional recommendations
└── README.md
```

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/adityapatel14/<repo-name>.git
cd internship_analysis

# Install dependencies
pip install pandas numpy matplotlib seaborn

# Run the notebook
jupyter notebook notebooks/internship_eda.ipynb
```

> For the Power BI dashboard, open `dashboard/internship_dashboard.pbix` in Power BI Desktop.

---

## 🔮 Future Improvements

- Expand dataset to include pre-COVID years (2018–2020) for a complete before/after comparison
- Add company-level analysis — which companies consistently offer paid internships
- Build a predictive model to forecast internship participation trends for upcoming batches
- Automate the dashboard refresh pipeline using Power BI dataflows

---

## 👤 Author

**Aditya Patel**
Aspiring Data Analyst | Python • SQL • Power BI • Machine Learning
[LinkedIn](https://www.linkedin.com/in/aditya-kaushik-patel) • [GitHub](https://github.com/adityapatel14) • [Email](mailto:akp2k4@gmail.com)
