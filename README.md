# Gig-Economy-Analysis-with-Tableau
A Data-Driven Exploration of Freelancer Earnings, Performance &amp; Market Trends

## Project Overview

This Tableau project provides a comprehensive analysis of 1,950 freelancers across multiple gig platforms, examining trends in earnings, job success, hourly rates, rehire patterns, and more. By integrating two key datasets—freelancer profiles and job performance metrics—I created **interactive dashboards** that answer strategic business questions for both freelancers and platform operators.

---

## Business Background

The gig economy is transforming how work is done—freelancers are now central to project delivery across industries. However, predicting earnings, success rates, and identifying in-demand skills remains a challenge.

FreelanceGig Analytics aims to bridge this gap using data. With this project, I analyzed:
- Earning trends by category and platform
- Job success and client rating metrics
- Hourly rate benchmarks by experience level
- Rehire rate as an indicator of trust and loyalty
- Forecasted earnings to guide freelancers’ future decisions

---

## Problem Statement

Despite rapid gig economy growth, freelancers and clients struggle to:
- Identify profitable niches and platforms
- Understand how experience impacts earnings
- Evaluate freelancer reliability
- Predict income for planning purposes

This project addresses those issues using **Tableau-powered dashboards** and **descriptive statistics**.

---

## Dataset Description

### `Freelancer_Details` Table

| Column | Description |
|--------|-------------|
| Freelancer_ID | Unique ID |
| Job_Category | Area of work (e.g., Web Dev, Graphic Design) |
| Platform | Source platform (e.g., Fiverr, Upwork, Toptal) |
| Experience_Level | Beginner, Intermediate, Expert |
| Client_Region | Geographic region of clients |
| Payment_Method | Method used to receive payment |

### `Job_Earnings` Table

| Column | Description |
|--------|-------------|
| Freelancer_ID | Foreign key |
| Jobs_Completed | Total jobs done |
| Earnings_USD | Total income in dollars |
| Hourly_Rate | Freelancer’s rate/hour |
| Job_Success_Rate | % of successful jobs |
| Client_Rating | Average client rating (1-5) |
| Job_Duration_Days | Time to complete a job |
| Project_Type | Fixed vs Hourly |
| Rehire_Rate | % of clients who returned |
| Marketing_Spend | Ad spend in USD |

---

## Tools Used

- **Tableau Public**
- Microsoft Excel (data cleaning)
- GitHub (version control & hosting)

---

## Dashboards Created

### 1. **Freelancer Performance Dashboard**
Tracks key metrics per freelancer including:
KPIs
- Job success rate
- Client rating
- Rehire rate
- Number of freelancers
  
Visualizations
- Top-paying platforms
- Platforms with highest success rates
- Rehire loyalty patterns per platform
- Average earnings by platform and experience level
- Hourly rate benchmarks

### 2. **Trend Dashboard**
Highlights:
- Marketing spend vs income trends
- Job duration variability

---

## Key Findings

**High Earners**:
- Freelancers in **App Development** and **Graphic Design** consistently earn the most.
- Experts earn higher hourly rates—often above $80/hr—compared to beginners.

**Job Success**:
- Platforms like **Freelancer** and **Toptal** show the highest success rates.
- Overall, freelancers have a strong average rating of **4.0/5**, indicating client satisfaction.

**Rehire Loyalty**:
- The average rehire rate is **44.6%**, a clear indicator of client trust.
- Some freelancers have up to **80%** rehire rate—valuable insight for clients and platforms.

**Marketing Spend**:
- Average marketing spend is **$248.5**.
- There’s no direct linear correlation between ad spend and income, suggesting diminishing returns or need for targeted promotion.

**Job Duration & Type**:
- Most projects last **~45 days**, with a wide spread from 3 to 89 days.
- Fixed projects tend to have better rehire rates than hourly ones.

---

## Recommendations

### For Freelancers:
- Focus on **high-paying categories** like Development & Design.
- Join platforms with higher **success and loyalty rates** (e.g., Toptal).
- Align **hourly rates** with experience level to remain competitive.
- Monitor **marketing ROI** and consider strategic rather than broad advertising.

### For Clients:
- Hire based on **job success + rehire rate**, not just hourly rate.
- Expect to pay more for experts—but receive better outcomes.
- Leverage dashboards to select the best freelancer for specific project types.

---

## What's Included in This Repo

| File | Description |
|------|-------------|
| `gig_freelancers_dataset.csv` | Cleaned dataset |
| `freelancer_tableau_dashboards.pdf` | Tableau dashboard file |
| `README.md` | Project documentation (this file) |

---

## Skills Demonstrated

✅ Tableau Dashboard Design  
✅ Storytelling with Data  
✅ KPI Tracking & Segmentation  
✅ Data Cleaning & Joining  
✅ Analytical Thinking & Recommendation Generation  
✅ Industry-Focused Use of Data (Gig Economy)

---

## Live Dashboard 

> If your Tableau dashboard is published, include the link:  
> 👉 [View Interactive Dashboard on Tableau Public](https://public.tableau.com/app/profile/oladayo.oladapo/viz/FreelanceGigAnalytics/PerformanceDashboard?publish=yes))



