# POWER BI

# 📊 Sales Report Dashboard

This dashboard analyzes company sales performance in **2021**. It transforms raw sales data into interactive visuals (charts, tables, and maps) to help managers and stakeholders quickly understand:

- Sales trends  
- Category performance  
- Geographic distribution  

The report focuses on product categories like **novelty items, supermarket goods, computers, gifts, and corporate supplies**.

## 🎯 Project Objective

Provide business intelligence insights to support decisions regarding:

- Product focus  
- Market expansion  
- Seasonal strategies  
- Overall sales performance  

The dashboard answers key questions about sales trends, category contributions, monthly fluctuations, and regional performance.

## 📂 Dataset Used

The dataset contains **12 months of sales records for 2021**, including:

- Date of sale (month/year)  
- Product category  
- Sales amount  
- Quantity sold  
- Geographic location (state/province)  
- Year  

### ✅ Download Dataset  
👉 [Download CSV](https://raw.githubusercontent.com/wisemansg/powerbi/main/assets/(PROJECT1)%20CustomerMaster.csv)

## 📊 Questions (KPIs)

- Total Sales  
- Total Quantity Sold  
- Year-over-Year (YoY) Change  
- Sales YTD (Year-to-Date)  
- Sales by Category  
- Sales by Month  
- Sales by Province/State  
- Quantity Trends  

## ⚙️ Process

**Data Preparation**  
- Cleaned data in Power BI  
- Standardized categories  
- Handled missing values  

**Data Modeling**  
- Created calculated columns for YTD, YoY, and cumulative metrics  

**DAX Metrics**  
- Total Sales  
- YoY % Change  
- Total Quantity  
- Category contribution  

**Analysis**  
- Monthly trends  
- Category comparison  
- Regional performance  

**Visualization**  
- Interactive dashboard with slicers  

## 🖼️ Dashboard Overview

![Sales Report Dashboard](https://raw.githubusercontent.com/wisemansg/powerbi/main/assets/Sales%20Report%20(1).png)

## 📅 Year Filters

- Select years (2018–2021)  
- Currently filtered to **2021**  

## 📊 Sales by Category

- **Novelty Shop**: ~$16M (~70%)  
- Supermarket: ~$2M  
- Computer: ~$2M  
- Gift: ~$2M  
- Corporate: ~$0  

💡 **Insight**: Heavy reliance on novelty items → diversification recommended.

## 📈 Monthly Sales Breakdown

| Month     | Sales   | YoY Change | YTD Sales |
|----------|--------|-----------|----------|
| January   | $4.44M | +3.1%  | $4.44M |
| February  | $4.24M | -4.3%  | $8.68M |
| March     | $4.58M | -8.2%  | $13.17M |
| April     | $4.59M | +11.4% | $17.76M |
| May       | $4.59M | -100%  | $22.36M |
| June      | $4.59M | -100%  | $22.36M |
| July–Nov  | $0     | -100%  | $22.36M |
| December  | $2.74M | -100%  | $22.74M |

💡 **Insight**: Strong first half, major drop in second half.

## 🗺️ Sales by Region

- **Top States**: California, Texas, New York  
- Lower performance: Midwest & Western regions  

💡 **Insight**: Opportunity for regional expansion.

## 📉 Quantity Trend

- High in January (~220K units)  
- Declines mid-year  
- Near zero in H2  

💡 **Insight**: Confirms sharp drop in demand or supply.

## 🔍 Key Insights

- Strong Q1 & Q2, weak H2 (-58% YoY)  
- Novelty category dominates (~70%)  
- Untapped regional markets  
- Possible operational/supply issues mid-year  

## ✅ Final Conclusion

This dashboard enables:

- Clear performance tracking  
- Identification of top categories  
- Early detection of sales decline  
- Better strategic decision-making  

## 🛠️ Tools Used

- Power BI  
- Power Query  
- DAX  
- Excel / CSV  

## 🔗 Live Dashboard

👉 [View Dashboard](https://app.powerbi.com/view?r=EXAMPLE_DUMMY_LINK)

---

# 📊 Web Marketing Performance Dashboard

## 🔍 Overview
The **Web Marketing Performance Dashboard** is a Power BI solution designed to evaluate digital marketing effectiveness and website engagement.

It provides insights into:
- Traffic acquisition channels  
- User engagement & bounce behavior  
- Page performance  
- Device & geographic trends  

👥 **Audience**: Marketing leaders, analysts, executives, and BI teams  

## 🎯 Business Objectives

- Understand traffic sources and campaign effectiveness  
- Evaluate user engagement and bounce rates  
- Identify high-performing pages and regions  
- Improve ROI and reduce inefficient marketing spend  

## 📂 Data Sources

- Google Analytics (web traffic & behavior)  
- Campaign attribution data  
- Device & geographic metadata  
- CSV / flat files  

## 🛠️ Tools & Technologies

- **Power BI Desktop** (Visualization)  
- **DAX** (Metrics & calculations)  
- **Power Query (M)** (Data transformation)  
- **Excel / CSV** (Data storage)  

## 🖼️ Dashboard Preview

![Web Marketing Dashboard](https://raw.githubusercontent.com/wisemansg/powerbi/main/assets/Web%20Marketing%20%20(1).png)

## 📊 Key Metrics

| Metric | Value |
|---|---|
| Total Sessions | 418K |
| Total Exits | 139K |
| Total Bounces | 90K |
| Avg Time on Page | 98.49 sec |
| Unique Pageviews | 325K |
| Avg Page Load Time | 54.39 sec |
| Latest Year Sessions | 189K |

## 📈 Insights

### Traffic Trends
- Steady session growth (Jan–Aug)  
- Engagement improving despite rising traffic  

### Device Performance
| Device | Sessions | Bounces |
|---|---:|---:|
| Desktop | 222K | 55K |
| Mobile | 113K | 31K |
| Tablet | 12K | 2.5K |

**Insight:**  
- Desktop = highest engagement  
- Mobile = higher bounce → needs UX optimization  
- Tablet = low impact  

### 📄 Top Pages (by Engagement)
- Page Title 496  
- Page Title 1827  
- Page Title 1788  
- Page Title 460  
- Page Title 1783  

**Insight:** Traffic is concentrated → strong candidates for SEO & conversion optimization  

### 🌍 Top Regions
1. United States  
2. India  
3. France  
4. United Kingdom  
5. Switzerland  

**Insight:** U.S. dominates → high ROI market  

## 🧠 Business Insights

- Strong traffic growth with improving engagement  
- Desktop remains primary conversion channel  
- Mobile experience needs optimization  
- High-performing pages drive majority of value  
- Geographic concentration highlights expansion opportunities  

## 🚀 Recommendations

- Optimize **mobile UX & load time**  
- Scale high-performing content (SEO focus)  
- Invest more in **top regions (U.S. & similar markets)**  
- Reallocate budget to high-performing channels  
- Integrate cost data for **CPA / ROAS analysis**  

## ⚠️ Limitations

- Last-click attribution model  
- Cookie tracking may undercount users  
- No cost data → limited ROI analysis  
- Geo data depends on IP accuracy  

## 🔮 Future Enhancements

- Multi-touch attribution  
- CRM integration (lead tracking)  
- Automated Google Analytics API pipeline  
- Predictive analytics (ML forecasting)  
- ROI metrics (CPA, ROAS)  

## ✅ Conclusion

This dashboard enables:
- Clear visibility into marketing performance  
- Data-driven campaign optimization  
- Better allocation of marketing resources  

It supports faster, smarter decision-making across digital marketing operations.

