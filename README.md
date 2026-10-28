# Employee_dataset_tableau

Explore 1,470 employees by state, department, job role, and hire year. Click a state to filter every chart. Sales and HR have the highest attrition rates, pay varies about 12x between roles, and hiring has rebounded 46% since its 2017 low.

# Employee Salary & Attrition Dashboard (Tableau)

**Live interactive dashboard:** [https://public.tableau.com/app/profile/tanatswa.chiwara/viz/EmployeeSalaryandAttrition_17926748673220/EmployeeSalaryandAttritionDashboard?publish=yes]

## Overview
An interactive Tableau dashboard of 1,470 employees showing headcount and pay by 
state, attrition by department, pay by job role, and hiring over time. Clicking a 
state filters the other charts.

## Business Questions
1. Where are employees based, and does pay differ by location?
2. Which departments lose the most people?
3. How does pay vary by job role?
4. How has hiring changed over time?

## Dataset
Employee HR dataset , 1,470 rows and 23 columns covering department, 
job role, state, salary, hire date, and attrition status. The fields used here had no 
missing values, duplicates, or inconsistent categories.
Salary currency is not specified in the source.

## Dashboard Views
| View | Question answered |
|---|---|
| Salary & Headcount by State | Where employees are based and how pay compares |
| Attrition by Department | Who leaves, split by department |
| Salary by Job Role | How pay differs across 13 roles |
| Hiring Trend | New hires per year, 2012-2022 |

## Key Findings
- **237 of 1,470 employees left (16.1%).**
- **Sales and HR have the highest attrition rates:** Sales 20.6% (92 of 446) and 
  HR 19.0% (12 of 63), vs Technology at 13.8% (133 of 961).
- **Technology still loses the most people.** It holds 65% of the workforce and 
  accounts for 56% of leavers (133 of 237).
- **Most employees are in California** (875, or 59.5%), then New York (419, 28.5%) 
  and Illinois (176, 12.0%).
- **Location barely affects pay.** Average salary was 114,059 in CA, 112,677 in IL, 
  and 110,772 in NY, all within 3% of each other.
- **Pay varies enormously by role,** about 12x from the lowest (Recruiter, 37.6K) 
  to the highest (HR Manager, 449K, though only 4 people hold that role).
- **There is a steep pay cliff.** Five management and senior roles average 286K-449K, 
  while the next tier (Machine Learning Engineer, 130K) is less than half the lowest 
  of them.
- **Seniority carries a large premium in technical roles.** Senior Software Engineers 
  average 126K vs 52K for Software Engineers (2.4x).
- **Hiring dipped to a low of 106 in 2017, then recovered** to its highest level of 
  155 in 2022, up about 46%.

## Recommendations
- **Focus retention work on Sales and HR first,** where the rates are highest, but 
  don't ignore Technology: its lower rate still means the largest number of departures.
- **Review the pay jump between mid-level and senior technical roles.** A 2.4x gap 
  can make mid-level staff feel stuck. Check it against attrition by role, which 
  this dashboard doesn't show.
- **Avoid state-based pay adjustments.** Pay differs by under 3% across states, so 
  location isn't driving compensation.
- **Plan for California concentration.** About 60% of staff in one state is a risk 
  worth planning around.
- **Match onboarding and capacity to the hiring rebound,** which has returned to its 
  2012 level.

## Limitations
- Only three states appear in the data, so a state map isn't informative. I used a 
  bar chart instead.
- Attrition is a snapshot with no leave dates, so trends in leaving can't be shown.
- Some roles have very few people (HR Manager has 4), so their averages are unstable.
- Findings are correlations, and the dataset appears to be anonymized or synthetic.

## Tools Used
Tableau Public
Excel
