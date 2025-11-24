# marketing-analysis
### **Challenge**

A marketing team needs to optimize budget allocation across multiple channels and campaign types to improve return on investment and reduce customer acquisition costs.

### Objectives

- Calculate and compare CAC and ROI across different marketing channels
- Analyze campaign performance by type (Awareness, Consideration, Conversion, Retention)
- Identify high-performing customer segments (age groups, email engagement)
- Provide data-driven recommendations to optimize marketing spend

### **Dataset & Tools**

Dataset by Rabie El Kharoua, used under CC BY 4.0. Synthetic dataset created for educational purposes. Original source: [Kaggle](https://www.kaggle.com/datasets/rabieelkharoua/predict-conversion-in-digital-marketing-dataset/data) ( 8,000 campaigns, 20 features).

Tools: Python (Pandas, Matplotlib, Seaborn), Jupyter Notebook

### **Approach**

1. Data Cleaning & Exploration
2.  Business Metrics Calculation
3. Segmentation Analysis
4. Data Visualization

### Links: [portfolio](https://www.notion.so/Anna-Sadrytska-Data-Analyst-Portfolio-28728cc1d21b80d48f1df5f5d8e1e585)

======================== KEY INSIGHTS ===========================

1) BEST PERFORMING CHANNEL:  
 
   Channel: PPC   

   CAC: $5612.07 (lowest)
 
   ROI: 24.7% (highest)

   Conversions: 1461
 
   → Why: Most cost-effective acquisition + highest return

2) UNDERPERFORMING CHANNEL:

   Channel: Email

   CAC: $5809.28 (highest)

   ROI: 20.5% (lowest)

   → Gap: 3.5% more expensive than best channel

   → Recommendation: Optimize or reduce budget

3) CHANNEL PERFORMANCE RANKING (by ROI):

   1. PPC           | CAC: $5612.07 | ROI:  24.7%
   2. SEO           | CAC: $5696.03 | ROI:  22.9%
   3. Referral      | CAC: $5700.61 | ROI:  22.8%
   4. Social Media  | CAC: $5718.21 | ROI:  22.4%
   5. Email         | CAC: $5809.28 | ROI:  20.5%

4) CAMPAIGN TYPE PERFORMANCE:

   Best: 'Conversion' (CAC: $5312.06)

   Worst: 'Awareness' (CAC: $5924.66)

   → Gap: 11.5% difference

5) ROI ANALYSIS:

   Average ROI: 22.7%

   Best: 24.7% (PPC)

   Worst: 20.5% (Email)

   → Spread: 4.2% between best and worst

6) EMAIL MARKETING INSIGHT:

   Clicked: 88.5% CR
   
   Opened only: 80.9% CR
   
   No engagement: 56.1% CR
   
   → Gap: 7.7% between clicks and opens

7) AGE SEGMENTATION:

   Best: 36-45 (90.1% CR)
   
   Worst: 65+ (86.1% CR)
   
   Average: 87.4% CR
   → Best group is 2.7% above average

8) CLICK-THROUGH RATE IMPACT:
   
   Converted: 0.1586 avg CTR
   
   Non-converted: 0.1280 avg CTR
   
   Difference: 23.9% higher for converters
   
   Correlation: 0.120 (weak positive)

9) OVERALL CAMPAIGN PERFORMANCE:

   Total Ad Spend: $40,007,559
   
   Total Conversions: 7,012
   
   Overall CAC: $5705.58
   
   Conversion Rate: 87.6%
   
   Estimated Revenue: $49,084,000
   
   Estimated Profit: $9,076,441
   
   Overall ROI: 22.7%


===========================RECOMMENDATIONS ===========================

PPC campaigns showed lower CAC and higher ROI, suggesting it’s worth focusing more on this channel and possibly increasing its budget., There’s also a noticeable gap between email opens and clicks — improving creatives or running A/B tests could help identify what drives higher engagement.
Additionally, the 36–45 age group shows the highest conversion potential, so creating tailored campaigns for this audience could bring better results.
Overall, segment-based A/B testing of marketing creatives would help refine the strategy and boost performance.
