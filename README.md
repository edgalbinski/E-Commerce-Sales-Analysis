# E-Commerce Sales Analysis

A comprehensive data analysis report examining 1,000 products across 7 categories with 12 months of sales data.

## 📊 Project Overview

The objective of this report is to identify the strengths, weaknesses, opportunities, and threats (risks) of the e-commerce business. Using these insights, I will provide clear, actionable recommendations to support strategic decision-making and business growth.

## 📈 Dataset Overview

Public Dataset available on [https://www.kaggle.com/datasets/fahmidachowdhury/e-commerce-sales-analysis]

- **Products:** 1,000
- **Categories:** 7 (Books, Toys, Sports, Electronics, Health, Clothing, Home & Kitchen)
- **Time Period:** 12 months of sales data
- **Metrics:** Sales volume, pricing, customer reviews (score & count), monthly performance

## 🔍 Key Findings

### 1. Top-Performing Product Categories

The market shows surprising balance with the top 3 categories (Books, Toys, Sports) commanding 46% of total sales.

![Category Performance](https://raw.githubusercontent.com/edgalbinski/E-Commerce-Sales-Analysis/main/viz1_category_performance.png)

**Key Insights:**
- **Books** leads with 938,229 units (15.59% market share) and $236.8M revenue
- **Toys** and **Sports** follow closely at ~15.2% market share each
- Only 3.26 percentage point spread between top and bottom categories
- Sports generates premium revenue relative to volume (#2 revenue, #3 volume)

### 2. Pricing Impact Analysis

**Critical Discovery: Price has virtually NO correlation with sales performance**

| Price Segment | Avg Sales | Avg Review Score | Product Count |
|---------------|-----------|------------------|---------------|
| Budget ($0-$100) | 6,096 | 3.00 | 219 |
| Mid-Range ($100-$200) | 5,985 | 3.07 | 195 |
| Premium ($200-$300) | 5,979 | 3.05 | 195 |
| Luxury ($300+) | 6,015 | 3.01 | 391 |

**Correlation Results:**
- Price vs. Sales: **-0.016** (no correlation)
- Price vs. Review Score: **+0.029** (no correlation)
- Top 50 sellers average **$212.96** vs. bottom 50 at **$269.97**

**Strategic Implication:** Quality, marketing, and product-market fit matter far more than price point.

### 3. Seasonal Sales Trends

**Surprising Finding: Remarkably flat seasonality with only 5.7% variance year-round**

![Seasonal Trends by Price Segment](https://raw.githubusercontent.com/edgalbinski/E-Commerce-Sales-Analysis/main/viz3_seasonal_by_price.png)

**Monthly Performance:**
- **Peak:** October (514,798 units, +2.62%)
- **Low:** May (487,194 units, -2.88%)
- **Average:** 501,659 units/month

**Quarterly Balance:**
- Q4: 25.3% | Q1: 25.1% | Q3: 25.0% | Q2: 24.6% (only 2.6% variance!)

#### Category-Specific Patterns

![Seasonal Trends by Category](https://raw.githubusercontent.com/edgalbinski/E-Commerce-Sales-Analysis/main/viz2_seasonal_by_category.png)

- **Clothing** (23% variation): Peaks in March (spring fashion), lows in January
- **Electronics** (17.5%): Peaks in January (post-holiday), not December
- **Toys** (13.2%): Peaks in February (birthday-driven, NOT holiday-driven!)
- **Books** (11.3%): Most consistent year-round

### 4. Customer Satisfaction Analysis

**⚠️ Critical Issue: Customer satisfaction is mediocre at 3.03/5.0**

![Satisfaction Distribution](https://raw.githubusercontent.com/edgalbinski/E-Commerce-Sales-Analysis/main/viz4_satisfaction_distribution.png)

**Alarming Statistics:**
- **37% of products rated "Poor" (≤2.5)** - quality crisis
- **Only 10.4% achieve "Excellent" (>4.5)**
- **61.8% score below 3.5 out of 5**

**Surprising Disconnect:** Poor-rated products (6,054 avg sales) actually outsell Excellent products (5,891 avg sales)
- Review Score vs. Sales correlation: **-0.018** (reviews don't drive purchases!)

#### Satisfaction by Category

![Category Satisfaction Scores](https://raw.githubusercontent.com/edgalbinski/E-Commerce-Sales-Analysis/main/viz5_category_satisfaction.png)

| Category | Avg Score | Status |
|----------|-----------|--------|
| Electronics | 3.14 | Highest ✅ |
| Books | 3.10 | Above Avg |
| Sports | 3.09 | Above Avg |
| Home & Kitchen | 3.04 | Average |
| Health | 3.01 | Below Avg |
| Clothing | 2.95 | Below Avg |
| **Toys** | **2.87** | **Lowest ⚠️** |

**Major Concern:** Toys ranks #2 in sales volume but has the worst customer satisfaction (2.87)

## 💡 Strategic Recommendations

### 🔴 WEAKNESS (Immediate Action Required)

1. **Product Quality Overhaul**: Audit and improve/remove the 370 products (37%) with poor ratings
2. **Toys Category Crisis**: Investigate why the #2 best-seller has the worst reviews (2.87 score)
3. **Target May-June slump** - promotional campaigns to boost summer sales
   
### 🔴 MAJOR RISK: 
1. **Brand Reputation** 37% poor-rated products, potential brand reputation damage
2. **Review System Audit**: Understand why negative reviews aren't preventing purchases yet

### 🟢 STRENGTHS (Boost What Works)

1. **Double down on Books, Toys, and Sports** - proven market leaders
2. **Leverage Electronics quality** - highest satisfaction (3.14); learn and replicate
3. **Capitalize on Oct-Feb strength** - aggressive marketing during peak period

### 🟢 STRATEGIC OPPORTUNITIES

1. **Premium pricing is safe** - focus on value perception over price reduction
2. **Home & Kitchen growth** - lowest market share (12.33%) offers expansion potential
3. **Category-specific seasonality** - tailor inventory and promotions (e.g., Clothing peaks in March)
4. **Stable cash flow** - minimal seasonality enables predictable financial planning




## 🎯 Business Impact

This analysis reveals a business with **strong fundamentals** (balanced portfolio, stable seasonality, price flexibility) but facing a **quality crisis** that threatens long-term sustainability:

✅ **Strengths:** Diverse revenue streams, year-round stability, pricing power  
⚠️ **Concerns:** Mediocre satisfaction (3.03/5.0), ineffective review system  
🔴 **Critical Risks:** 37% poor-rated products, brand reputation vulnerability
🎯 **Opportunities:** Premium pricing is safe, and 'Home & Kitcken' has expansion potential

**Bottom Line:** Immediate action on product quality—especially in the Toys category and among the 370 poorly-rated products—is essential to prevent customer attrition and protect brand equity.

## 🚀 Key Takeaways

1. **Price doesn't predict sales** - focus on product quality and marketing instead
2. **Seasonality is minimal** - provides business stability and predictable planning
3. **Customer satisfaction is a ticking time bomb** - 37% poor ratings demand urgent attention
4. **Reviews don't prevent purchases** - but poor quality will hurt long-term retention
5. **Category balance is healthy** - no over-dependence on single revenue stream

---

## 👨‍💻 Author

**Eduardo Galbinski Rodrigues**  
📍 Data Analyst | Background in SMB Development & SMB Financial Sales |

📧 [dudugr03@gmail.com](mailto:dudugr03@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/edgalbinski/)  
💻 [GitHub](https://github.com/edgalbinski)

---

> ⭐ *If you found this project insightful, consider starring the repository to support my work!*  
