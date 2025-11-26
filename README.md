# Adventure-works-customer-details-dashboard-
Fully interactive Power BI dashboard exploring Adventure Works customer sales (2015–2017). Features revenue trends, geographic insights, product performance ranking, and target tracking, built with best-practice DAX, star-schema modeling, and optimized for Power BI Service.
## Dashboard Overview
This dashboard provides actionable insights into customer behavior, product performance, and geographic trends for Adventure Works Cycles.
## Dataset Source
<a href=https://github.com/GeharaRathnayake/Adventure-works-customer-details-dashboard-/tree/main/Lab%20sheet%20data>Lab Sheet Data</a>
## Dashboard
<img width="1167" height="662" alt="Adventure Works Customer Details Dashboard" src="https://github.com/user-attachments/assets/5d478cf3-435c-47f1-88f3-7e1078ef4748" />


### Key Insights & Visuals Included
- Total Orders: **11,724** | Total Revenue: **$9.7M+**
- Revenue & Order Trends (2015–2017)
- Top-selling products and sub-categories
- Customer segmentation by Gender, Age, Continent, and Country
- Performance against order targets (Gauge visual)
- Interactive filters: Continent, Year, Product Category, Gender
  
| Metric                  | Value            | Key Insight                                      |
|-------------------------|------------------|--------------------------------------------------|
| Total Orders            | **11,724**       | Steady volume with strong seasonal peaks         |
| Total Revenue           | **$9,708,245**   | Driven by high-margin accessories                |
| Top Region              | North America    | 70%+ of business — heavy geographic concentration |
| Core Customer           | Males, Age 50–70 | Dominant segment; females under-served           |
| Top Revenue Product     | Hitch Rack – 4-Bike | $21.2M from just 183 orders → high value         |
| Fastest Growing Period  | 2016 → 2017      | ~50% YoY revenue jump after mid-2016 dip         |
| Target Achievement      | Only **50%**     | Orders significantly below goal                  |

### Critical Business Questions Answered
- Sales grew strongly from 2015 to 2017, with a noticeable dip mid-2016 followed by a sharp rebound.
- North America dominates; Europe & Pacific represent clear growth opportunities.
- Accessories (especially bike racks and tires) generate disproportionate revenue vs. volume.
- Female customers and younger segments are under-represented → marketing opportunity.
- Company consistently misses order volume targets despite strong revenue.

### Conclusions & Strategic Recommendations
1. **Geographic Risk**: 70%+ revenue from North America → prioritize Europe/Pacific expansion.
2. **Gender Opportunity**: Females are 43% of orders but likely higher potential → launch targeted campaigns.
3. **Product Focus**: Double down on high-margin accessories (Hitch Racks, Tires & Tubes).
4. **Seasonality Leverage**: Capitalize on summer peaks (June–July) with promotions to close target gaps.
5. **Cloud Monitoring**: Deploy this dashboard to Power BI Service with scheduled refresh + alerts for real-time tracking.
## Dashboard Visualizations (Fully Interactive)

| Visualization                  | Type               | Key Metrics Shown                                  | Purpose / Insight Delivered                              |
|--------------------------------|--------------------|----------------------------------------------------|-----------------------------------------------------------|
| Total Sales by Country         | Filled Map         | Total Sales (color saturation + bubble size)      | Instantly spot top-performing countries & growth opportunities |
| Sales, Gross Margin & Margin % over Time | Area + Line Chart  | Total Sales, Gross Margin ($), Margin %            | Track profitability trends and seasonality in one view     |
| Gross Margin by Product        | Donut Chart        | Gross Margin ($) by individual Product             | Highlight most profitable products at a glance             |
| Gross Margin by Year           | Pie Chart          | Gross Margin split by Year                         | Quickly compare year-on-year profitability contribution    |
| Total Sales by Segment         | Horizontal Bar Chart | Total Sales by Customer Segment (Consumer, Corporate, etc.) | Identify which customer segment drives revenue            |
| Sales & Margin % by Country    | Clustered Column Chart | Total Sales + Margin % side-by-side per country   | Compare revenue volume vs. profitability across regions   |

### Highlights
- Built using **Power BI Desktop** + optimized for **Power BI Service (cloud)**
- Clean and modern UI with conditional formatting and tooltips
- Fully interactive slicers and cross-filtering
- Mobile-responsive layout tested

## Skills Demonstrated (Highly Relevant for Business Analytics & Cloud Intern Roles)
| Skill                        | Applied In This Project                              |
|-----------------------------|-------------------------------------------------------|
| Power BI (Cloud + Desktop)  | Full dashboard development & publishing to cloud     |
| DAX                         | Calculated columns, measures (YoY growth, rankings)   |
| Data Modeling              | Star schema, relationship management                  |
| Data Cleaning & Transformation | Power Query (M language)                         |
| Interactive Visualization  | Slicers, drill-through, bookmarks                    |
| Geographic Analysis         | Map visuals with location hierarchy                   |

## How to Open & Explore
1. Download the `.pbix` file
2. Open with **Power BI Desktop** (free download: [powerbi.microsoft.com/desktop](https://powerbi.microsoft.com/desktop/))
3. Explore data model, DAX measures, and visuals
4. Publish to your own Power BI Service to experience cloud features

## Why This Project Stands Out for Internships
- 100% built from scratch (no templates)
- Cloud-ready (designed for Power BI Service sharing & app workspace deployment)
- Real-world business questions answered
- Clean code + professional formatting → instantly impresses recruiters

Perfect for roles like:  
**Business Analytics Intern | Data Analyst Intern | BI Developer Intern | Cloud Analytics Intern**
