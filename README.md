# Amazon Product Review Analytics Dashboard (Power BI)

## Overview
This project presents an interactive, multi-page Power BI dashboard developed to analyze Amazon product data across pricing, discounting, ratings, and review reliability. It is designed to support decision-making in product management, marketing strategy, and customer experience evaluation.
The report leverages calculated DAX measures, dynamic visual elements, and clean visual design to deliver insights into how pricing and promotional strategies impact customer satisfaction, while also identifying patterns of potentially unreliable product ratings.

---

## Key Features

- **Dynamic Metric Toggle**  
  Users can switch between price-based, discount-based, and rating-based views using DAX-driven logic.

- **Top/Bottom N Sub-Category Ranking**  
  Flexible ranking controls allow users to explore top or bottom product segments across key metrics.

- **Discount vs. Rating Correlation Analysis**  
  Visual exploration of how discount percentages influence average product ratings.

- **Review Quality Flags**  
  Products with high ratings but very few reviews are flagged as potentially unreliable.

- **Strategic Price Segment Evaluation**  
  Products are grouped into Budget, Mid-Range, Premium, and Luxury tiers, allowing analysis of performance by price bracket.

---

## Use Cases

1. **Pricing Strategy Optimization**  
   Identify pricing tiers that consistently yield higher customer satisfaction.

2. **Product Quality Assurance**  
   Detect products with unreliable review signals to guide moderation and curation.

3. **Marketing and Promotion Analysis**  
   Assess how discounting impacts perception and review behavior.

4. **Category Management**  
   Understand which categories consistently perform well across different consumer metrics.

5. **Customer Experience Evaluation**  
   Track satisfaction trends across segments to support product development and service improvements.

---

## Tools & Technologies

- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Power Query (for data shaping)**
- **Custom JSON Theme (Amazon branding-inspired)**
- **Kaggle Dataset: Amazon Products**

## Sample 
Which product sub-categories offer the highest average discounts?
![image](https://github.com/user-attachments/assets/c0f76a6c-ddf5-4a8c-afc6-f65d5f4c430b)

**Within the Accessories category, the product sub-categories offering the highest average discounts are:**
-Fashion & Silver Jewellery (~64%)

-Jewellery (~58%)

-Handbags & Clutches, Bags & Luggage, and Watches (each ~52–54%)

-This suggests that fashion-related accessories in this category are being aggressively discounted, likely to drive volume-based sales or clear inventory.

-In contrast, Gold & Diamond Jewellery shows a significantly lower average discount (~33%), which may reflect higher value perception or limited markdown strategies due to premium pricing.


Does offering higher discounts lead to higher customer satisfaction?
![image](https://github.com/user-attachments/assets/5325e31b-a6aa-4bce-860e-6605629202de)
**Based on products with over 1,000 reviews across all categories:**

-Products with discounts over 50% have an average rating of 2.52

-Products with discounts below 50% average just 2.01 stars

-The highest-rated group comes from the 71%+ discount bucket, suggesting deep discounts may attract more satisfied or less demanding customers

-Products in the 11–30% discount range show the lowest average ratings (~2.0), indicating this segment may reflect underperforming items with modest price cuts

**Insight:**

-Higher discounts do not guarantee better ratings, but extreme discounts may be more appealing than modest ones

-Moderate discounts (11–30%) may not meet customer value expectations, possibly leading to lower satisfaction


