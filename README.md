## Meta Ads Campaign Performance Analysis
![E-commerce Dashboard]

An end to end data analysis project analyzing **257 Meta Ads campaings** to identify profitable vs loss making campaigns, engineer marketing KPIs and build 4-page Power BI dashboard for budget optimization decisions and design a **₹10 Lakh, 6-month budget allocation model** projecting 
**₹30.24 Lakh revenue and ₹20.24 Lakh profit (202% ROI)**.

---

## Business Problems
A company ran 257 ad campaigns on meta (Facebook + Instagram) and didn"t know which campaigns were profitable.

- Which campaigns should we **scale**?
- Which campaigns should we **pause**?
- Which campaigns should we **stop immediately**?
- Where is our **wasted spend** concentrated?
- Which **city, platform, or creative** delivers the best ROAS?

---

## Tools & Technologies
Python (Pandas, NumPy) | Power BI | DAX | Power Query | Excel

---

## Analysis Approach
1. Cleaned raw data (dates, platforms, nulls, duplicates)
2. Engineered 8 KPIs: CTR, CPC, CPA, CVR, CPL, ROI, ROAS, Frequency
3. Multi-Level Analysis on 257 ad campaigns
4. Classified campaigns into Continue (55) / Pause (34) / Discontinue (168)
5. Built 4-page (Executive Summary, Profitability & Decision Analysis, Platform, Creative & Audience Analysis and City Performance Analysis) Power BI dashboard

---

## Data Cleaning Steps
The raw dataset had multiple data quality issues that were resolved:
- Mixed date formats
- Inconsistent platform names
- Status case variations
- Region trailing spaces
- Duplicate campaign IDs
- Null values in `region`, `objective`, `placement`
- Divide-by-zero errors in KPI columns

---

## KPIs Engineered

| KPI | Formula | Purpose |
|-----|---------|---------|
| **CTR** | (Clicks / Impressions) × 100 | Ad engagement |
| **CPC** | Spend / Clicks | Cost per click |
| **CPA** | Spend / Purchases | Cost per acquisition |
| **CVR** | (Purchases / Clicks) × 100 | Conversion rate |
| **CPL** | Spend / Leads | Cost per lead |
| **ROI** | ((Revenue − Spend) / Spend) × 100 | Return on Investment |
| **ROAS** | Revenue / Spend | Return on ad spend |
| **Frequency** | Impressions / Reach | Ad repetition |

---

## Campaign Problem
1. There are 168 Discontinue campaigns with ₹6.10 lakhs spend.
2. There are 34 pause campaigns
3. Ahmedabad (0.64x Roas), Pune (0.75x Roas), chennai (0.76x Roas), Jaipur (0.82x Roas) and Delhi Ncr (0.86x Roas) has low revenue with high spend.
4. Tablet has negative ROI (-17.60%).
5. Only Reel (-30.39% ROI) has performed negative.
---

## Campaign status
Continue = 55
Pause = 34
Discontinue = 168

---

## Key Insights
1. **Only 21% of campaigns are profitable** - 55 out of 257
2. **65% of capaigns are loing money** - 168 out of 257
3. **Top performer by ROI** - C182 - ROI 891%
4. **Best city by ROAS** - Gurgaon
5. **Top performer by ROAS** - C182 — ROAS 9.91x, CPC ₹0.72
6. **Best platform** - Instgram
7. **Best Creative** - Video + Carousel outperform static images
8. **Best audience** - Lookalike 1% > Interest-based > Broad
9. **Wasted spend on Discontinue campaigns** - ₹6.10 lakhs
10. **Flagged high-spend, low-efficiency campaigns** - 85 Campaigns

---

## Business Recommendations
1. Immediately stop all 168 Discontinue campaigns.
2. Scale the 55 Continue campaigns - Top 10 go to Winners (₹5L budget).
3. Fix the 34 Pause campaigns - 48% of Optimize budget to funnel deep-dive
4. Test & Learn 5 strategic experiments using 40% success rate.
5. Hold ₹1L buffer for festivals, winning tests, competitor attacks.

---

##  ₹10 Lakh Budget Allocation Model
 Winners = ₹5,00,000
Optimize = ₹2,00,000
Test & Learn = ₹2,00,000
Buffer = ₹1,00,000

---

## Projected Outcomes
Total Spend = ₹10,00,000
Total Revenue = ₹30,24,172.89
Total Profit = ₹20,24,172.89
Overall ROAS = 3.02x
Overall ROI = 202.42%

---

## Bucket-by-Bucket Breakdown
| **Bucket** | **Budget** | **Expected ROAS** | **Revenue** | **Profit** |
|-----|---------|---------|---------|---------|
| Winners | ₹5,00,000 | 4.50x | ₹22,50,000 | ₹17,50,000 |
| Optimize | ₹2,00,000 | 2.74x | ₹5,48,000 | ₹3,48,000 |
| Test & Learn | ₹2,00,000 | 1.95x (60% success) | ₹3,90,000 | ₹1,90,000 |
| Buffer | ₹1,00,000 | 3.02x (weighted) | ₹3,02,000 | ₹2,02,000 |
| **Total** | **₹10,00,000** | **3.02x** | **₹30,24,172** | **₹20,24,172** |

---

## Power BI Dashboard
Page 1 — Executive Summary
[https://screenshots/page1_executive.png](https://github.com/princesaini05/Meta-Ads-Campaign-Performance-Analysis/blob/eb132f0697c2cb0047693a330678aef934cba735/Power%20BI%20dashboard/screenshots/01_Executive%20Summary.png)

Page 2 — Profitability & Decision Analysis
https://screenshots/page2_profitability.png

Page 3 — Platform & Creative
https://screenshots/page3_platform.png

Page 4 — City Performance
https://screenshots/page4_city.png

---

## Results Summary
| **Metric** | **Value** |
|---------|---------|
| Campaigns analyzed | 257 |
| Total budget modeled | ₹10,00,000 |
| Projected revenue | ₹30,24,172.89 |
| Projected profit | ₹20,24,172.89 |
| Overall ROAS | 3.02x |
| Overall ROI | 202.42% |
| Campaigns to Continue | 55 |
| Campaigns to Pause | 34 |
| Campaigns to Discontinue | 168 |
| Flagged campaigns | 85 |
| Dashboard pages | 5 |

---

## Author
[Prince]
Email: [princesaini6914@email.com]
