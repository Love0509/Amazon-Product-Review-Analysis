# Amazon-Product-Review-Analysis
Data analysis project  focused on extracting insights from product and customer review data to support product improvement, marketing strategy, and customer engagement.


## 1. Poject Description

This project was completed as part of the DIGITAL SKILLUP AFRICA CPSTONE PROJECT, working as  a **Junior Data Analyst** at *RetailTech Insights*, an e-commerce analytics company that supports sellers on platforms using Amazon as a case study.

The focus of this analysis is on product and customer review data, with the objective of uncovering insights to drive:

- **Product Improvement**
- **Marketing Strategy Optimization**
- **Customer Engagement Enhancement**
 
## 2. Dataset Description 
The dataset contains information scraped from Amazon product pages, including: 
- Product details: name, category, price, discount, and ratings 
- Customer engagement: user reviews, titles, and content 
- Each row represents a unique product, with aggregated reviewer data 
stored as comma-separated values 
- Total Records: 1,465 
- TotalFields: 16 columns
- 
## 3.  Key Highlights
- Performed exploratory data analysis (EDA) on product reviews
- Analyzed review sentiment and trends over time
- Identified high-performing and underperforming product categories
- Generated visualizations and dashboards using Pivot Tables in Microsoft Excel to present findings
 
## 4. Task Analysis and findings
1. What is the average discount percentage by product category?
   - **Methododology:**  Made use of an Excel pivot tale. The product category was placed in the "rows field" while discount percentage was placed in the "values field" and summarized in average.

   - **Result:**
  
 | Row Labels            | Average of discount_percentage |
|-----------------------|--------------------------------|
| HomeImprovement       | 58%                            |
| Computers&Accessories | 54%                            |
| Health&PersonalCare   | 53%                            |
| Electronics           | 51%                            |
| MusicalInstruments    | 46%                            |
| Car&Motorbike         | 42%                            |
| Home&Kitchen          | 40%                            |
| OfficeProducts        | 12%                            |
| Toys&Games            | 0%                             |
| Grand Total           | 48%                            |

   -     
Out of 1,465 total products, the majority fall under:
Electronics (526)
Computers & Accessories (453)
Home & Kitchen (448)
These top three categories make up over 97% of all products.
Other categories like Office Products, Musical Instruments, and Home Improvement have minimal listings, while a few categories have just 1 product each, indicating limited catalog presence.
     
2. How many products are listed under each category?


3. What is the total number of reviews per category?  
4. Which products have the highest average ratings? 
5. What is the average actual price vs the discounted price by category? 
6. Which products have the highest number of reviews? 
7. How many products have a discount of 50% or more? 
8. What is the distribution of product ratings (e.g., how many products are rated 3.0, 
4.0, etc.)? 
9. What is the total potential revenue (actual_price × rating_count) by category? 
10. What is the number of unique products per price range bucket (e.g., <₹200, 
₹200–₹500, >₹500)? 
11. How does the rating relate to the level of discount? 
12. How many products have fewer than 1,000 reviews? 
13. Which categories have products with the highest discounts? 
14. Identify the top 5 products in terms of rating and number of reviews combined.
