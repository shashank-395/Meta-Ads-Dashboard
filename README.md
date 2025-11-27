# 📊 Meta Ad Performance Analysis – Power BI Project

## 📌 Project Overview  
This Power BI dashboard provides a complete analysis of advertising campaigns run on **Facebook and Instagram (Meta Ads)**.  
It offers insights into:

- Ad reach & impressions  
- Engagement patterns  
- Conversions & purchases  
- Audience demographics  
- Geographic performance  
- Ad formats & budget utilization  

The analytics follow the complete **marketing funnel**:  
**Impressions → Clicks → Engagements → Purchases**

This dashboard helps marketing teams to:

- Identify top-performing platforms and ad types  
- Optimize campaign budgets  
- Improve targeting accuracy  
- Understand audience behavior across segments  

---

## 🚀 Key Business Questions Answered  

- Which ads and campaigns performed the best?  
- What is the ROI and funnel efficiency?  
- Which audience segment engaged the most?  
- What are the best time periods to run ads?  
- Which regions and demographics delivered the strongest results?  
- Which ad formats (Video, Image, Stories, Carousel) generate the most conversions?  

---

## 🧠 Data Model Overview  

The project uses 4 core tables:

| Table | Type | Description |
|-------|------|-------------|
| **ad_events** | Fact | Contains impressions, clicks, purchases, timestamps |
| **ads** | Dimension | Platform, ad type, targeting attributes |
| **campaigns** | Dimension | Campaign budgets and schedules |
| **users** | Dimension | Demographic and geographic user information |

### 📐 Modeling Approach  
- **Star Schema**  
- **One-to-many relationships**  
- **Dedicated Date Table** for time intelligence  
- **DAX-based measures** for metrics like CTR, CPC, CPM, ROAS, Funnel Drop-off  

---

## 🎯 Business Impact  

This report enables teams to:

- Optimize budget allocation  
- Improve ad targeting and personalization  
- Identify top-performing regions & demographics  
- Boost conversion rates by addressing funnel leakage  
- Schedule ads during high-engagement windows  
- Prioritize high-ROI ad formats  
---

