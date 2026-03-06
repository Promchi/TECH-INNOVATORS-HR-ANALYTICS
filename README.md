# 📊 Tech Innovators Inc — Employee Performance & Benefits Analysis

## Project Overview
Tech Innovators Inc needed to understand the relationship between employee benefit programmes, training completion, and performance outcomes. This project delivers a data-driven framework analysing 244 employees across 7 departments — translating HR data into actionable insights for leadership via interactive Tableau dashboards.

📁 **Full Project Files** (Tableau workbook, documentation, presentation, datasets):
[Google Drive Folder →](https://drive.google.com/drive/folders/1Hv5M1uuynmu1nNl0xufaYdjULpi7pV7q?usp=sharing)

---

## Business Problem
The HR department at Tech Innovators Inc. faced two interrelated challenges impacting overall HR strategy and operational efficiency:

**1. Limited Visibility into Real-Time Performance**
While a performance review system existed, it lacked the analytical depth needed for proactive workforce management. HR leadership could not quickly identify underperforming employees, recognise high performers for targeted development, or intervene before performance issues escalated. Interventions were delayed, inconsistent, and reactive rather than proactive.

**2. Inefficient Employee Benefit Programmes**
Tech Innovators offered a range of benefits including health insurance, gym membership, paid time off, and wellness programmes. However, the company had limited insight into utilisation patterns, satisfaction levels, and return on investment — leading to escalating costs and inefficient resource allocation.

**Business Impact:**
- Operational inefficiency from lack of performance visibility caused delays in promotions, training, and development interventions
- Inability to track benefit usage accurately resulted in overspending on underutilised programmes
- Inadequate benefit offerings combined with delayed performance feedback led to disengagement and elevated turnover risk

---

## Business Questions Answered
- What is the overall employee performance rating and how does it vary across departments?
- Do employees who utilise benefits perform better than those who don't?
- Does training completion have a measurable impact on performance?
- Which benefits are most utilised and which are most satisfying to employees?
- Are there demographic patterns (age, department) in performance that signal future organisational risks?

---

## Key Findings

### 📈 Performance & Benefits
- **Overall average Quarterly Performance Rating (QPR): 71.17%** across 244 employees in 7 departments
- Employees who utilised benefits showed an **18.81% increase in QPR** versus their previous quarter
- Employees who combined benefits with training completion showed a **37.87% QPR increase**
- Employees who used benefits but did not complete training showed only a **4.68% increase** — proving training is the critical performance multiplier, not benefits alone

### 🎓 Training Effectiveness
- **Only 48.77% of employees have completed training** — over half the workforce is operating below its performance potential
- The 33 percentage point gap between trained (+37.87%) and untrained (+4.68%) employees makes training completion the highest-leverage intervention available to HR leadership

### 🏥 Benefit Utilisation & Satisfaction
- **584 total benefit utilisations** across the workforce — employees may use multiple benefit types
- **Health Insurance** is the most utilised benefit
- **Gym Membership** has the highest satisfaction rate at **41.29%** — despite not being the most used
- This gap between utilisation and satisfaction signals an opportunity to promote wellness benefits more actively

### 🏢 Departmental & Demographic Insights
- The **IT department** has the highest benefit usage (162 utilisations) but only a **20.79% average performance score** — demonstrating that benefits alone do not drive performance without training
- **Legal and HR departments** are high performing at **32.00% and 25.00%** respectively despite lower benefit usage
- Employee distribution is concentrated in the **31–44 age group** — the organisation's core workforce
- A **positive age-value correlation** exists — performance improves with experience and tenure
- The small number of senior employees signals a **potential future leadership gap**

---

## Recommendations
1. **Make training mandatory** — the 37.87% vs 4.68% performance gap is too significant to ignore. Introduce flexible learning formats and tie completion to performance review cycles
2. **Promote wellness benefits** — Gym Membership has the highest satisfaction despite not being the most used. Targeted internal communications could close this gap at no additional cost
3. **Develop future leaders** — with most employees aged 31–44, leadership development and mentorship programmes should be introduced now to prevent a future leadership gap
4. **Address the IT paradox** — highest benefit usage but below-average performance signals a structural training gap that warrants a focused departmental review

---

## Tools & Technologies
| Tool | Purpose |
|------|---------|
| Google Sheets | Preliminary data screening and quality checks |
| Tableau | Data integration, calculated fields, interactive dashboards |

---

## Data & Structure
- **3 datasets:** Employee Benefits (584 rows), Employee Demographics (244 rows), Employee Performance (244 rows)
- Datasets joined on Employee ID in Tableau
- Custom calculated field: Age Group segmentation using IF statement in Tableau
- All datasets available in the `data/` folder on Google Drive

---

## Dashboards
- **Employee Benefits Overview** — benefit utilisation by type, satisfaction rates, departmental breakdown
- **Employee Performance Dashboard** — QPR trends, training impact, age group and departmental performance

---

## Deliverables
- ✅ Interactive Tableau dashboards (.twbx)
- ✅ Professional project documentation (.docx)
- ✅ Executive PowerPoint presentation
- ✅ Raw datasets (CSV)

---

*Project completed March 2026 | Data Analytics Consultant at AMDARI*
