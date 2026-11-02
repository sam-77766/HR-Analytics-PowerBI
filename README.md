# 👥 HR Analytics Dashboard (Power BI)

An interactive 4-page **Power BI** dashboard that analyzes data of **1,470 employees** to help
HR and management understand workforce structure, **attrition (turnover)**,
compensation, and performance.

## 📌 Project Overview
The report answers key HR questions:
- How big is the workforce and who are our employees (age, gender, education, marital status)?
- What is the attrition rate, and which departments, roles, and age groups lose the most people?
- Do overtime, work-life balance, environment satisfaction, or tenure influence attrition?
- How do salary, training, job satisfaction, and performance ratings compare across departments and roles?

## 🖼️ Dashboard Preview
![Overview](screenshotsoverview.png)
![Demographics](screenshotsdemographics.png)
![Attrition](screenshotsattrition.png)
![Performance](screenshotsperformance.png)

## 📑 Report Pages

### 🏠 Overview
- **KPIs:** Total Employees, Employees Left, Attrition Rate, Average Monthly Income, Average Job Satisfaction, Average Age
- **Visuals:** Attrition by Department, Job Role, Gender, Age Group, Years at Company, and Overtime vs Attrition

### 👥 Demographics
- **KPIs:** Average Age, Average Education Level, Average Total Working Years, Average Years at Company
- **Visuals:** Employees by Gender, Job Role, Business Travel, Marital Status, Department, and Education Field

### 📈 Attrition
- **KPIs:** Employees Left, Attrition Rate, Department with Highest Attrition
- **Visuals:** Attrition by Department, Overtime, Environment Satisfaction, Work-Life Balance, Age Group, and Marital Status

### ⭐ Performance
- **KPIs:** Average Monthly Income, Performance Rating, Job Satisfaction, Training Times Last Year
- **Visuals:** Average Salary by Department and Job Role, Training Times, Monthly Income vs Performance Rating, Job Satisfaction and Performance Rating distributions

Every page includes interactive **slicers** and a **page navigator**.

## 🔎 Key Insights

**Overall picture**
- The company has **1,470 employees**, and **237 of them left**, an overall **attrition rate of 16.1%**.
- Average age is **36.9 years**, average tenure is **7.0 years**, and average monthly income is **6,503**.
- About **28.3%** of employees work overtime.

**Who is leaving?**
- **Overtime is the strongest signal:** attrition is **30.5%** for employees working overtime vs only **10.4%** for those who don't, about **3x higher**.
- **Sales Representatives** have the highest attrition rate at **39.8%**, followed by Laboratory Technicians (**23.9%**) and HR (**23.1%**). Research Directors (**2.5%**) and Managers (**4.9%**) are the most stable.
- **Young employees leave the most:** **39.2%** attrition under age 25, vs about **10%** for ages 35 to 54.
- **New joiners are at risk:** employees in their first year show **34.9%** attrition, dropping to **8.1%** after 10+ years.
- **Single employees** leave at **25.5%**, vs **12.5%** for married and **10.1%** for divorced employees.
- **Frequent business travelers** have **24.9%** attrition vs **8.0%** for those who don't travel.
- **Low work-life balance** (**31.2%**) and **low environment satisfaction** (**25.4%**) are linked to much higher attrition.

**Departments**
- **Sales** has the highest attrition **rate** (**20.6%**), followed by HR (**19.0%**) and R&D (**13.8%**).
- **R&D** has the highest attrition **count** (**133 employees**) because it is the largest department (961 employees).

**Compensation & performance**
- Employees who left earned on average **4,787** per month vs **6,833** for those who stayed, about **30% less**.
- Average monthly income ranges from **2,626** (Sales Representative) to **17,182** (Manager).
- Performance ratings are concentrated at **3** (1,244 employees) and **4** (226 employees), with an average of **3.15**.
- Gender split is **60% male / 40% female**, and attrition is slightly higher among men (**17.0%** vs **14.8%**).

## 💡 Recommendations
- Review **overtime** policies and workload, especially in Sales and Lab Technician roles.
- Strengthen **onboarding and support in the first year**, and create growth paths for employees under 35.
- Revisit **compensation** for low-paid, high-attrition roles such as Sales Representatives.
- Reduce travel load or offer flexibility for frequent travelers.

## 🛠️ Tools & Skills
- **Power BI Desktop**
- **DAX** measures (Total Employees, Employees Left, Attrition Rate, Overtime Rate, Department/Job Role with Highest Attrition, and more)
- **Calculated columns** (Age Group, Environment Satisfaction Level, Work-Life Balance Level, Job Satisfaction Level)
- **Data cleaning & modeling** and **dashboard design** (KPI cards, custom icons, slicers, page navigation)

## 📂 Repository Structure
```
├── HR_ANALYSTIC_3.pbix   # Power BI report
├── screenshots/          # Dashboard images
└── README.md
```

## ▶️ How to Open
1. Download `HR_ANALYSTIC_3.pbix`
2. Open it with [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free, Windows)

## 👤 Author
** Name: Hossam Abdelfattah
- LinkedIn: [https://www.linkedin.com/in/hossam-abdelfattah-]


