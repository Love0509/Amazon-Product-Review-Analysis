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

    
  - **Insights:**
 
     Home Improvement products have the highest average discount at 58%, followed closely by Computers & Accessories (54%) and Health & Personal Care (53%), suggesting aggressive pricing strategies in these categories. In contrast, Office Products (12%) and Toys & Games (0%) have significantly lower or no discounts, indicating either low competition or premium pricing.
    
2. How many products are listed under each category?

    - **Methodology:** Usng Pivot table, Product category was placed in the 'row field' while product_name was placec in the 'values field' summarized as count values.
  
    - **Result:**
  
| Row Labels            | Count of Product Name |
|-----------------------|-----------------------|
| Electronics           | 526                   |
| Computers&Accessories | 453                   |
| Home&Kitchen          | 448                   |
| OfficeProducts        | 31                    |
| MusicalInstruments    | 2                     |
| HomeImprovement       | 2                     |
| Car&Motorbike         | 1                     |
| Toys&Games            | 1                     |
| Health&PersonalCare   | 1                     |
| Grand Total           | 1465                  |


   -  **Insights:**
The dataset contains a total of 1,465 products, distributed across various categories. 
The breakdown reveals that:
  
  Out of 1,465 total products, the majority fall under:
Electronics (526)
Computers & Accessories (453)
Home & Kitchen (448). These top three categories make up over 97% of all products.

Other categories like Office Products, Musical Instruments, and Home Improvement have minimal listings, while a few categories have just 1 product each, indicating limited catalog presence.


3. What is the total number of reviews per category?
  
   - **Methodology:**  Utilized an Excel Pivot table. Product category was placed in the 'row field' while Rating count was placec in the 'values field' summarized as count values.
  
    - **Result:**

| Row Labels            | Sum of rating_count |
|-----------------------|---------------------|
| Car&Motorbike         | 1118                |
| Computers&Accessories | 7765029             |
| Electronics           | 15778848            |
| Health&PersonalCare   | 3663                |
| Home&Kitchen          | 2991069             |
| HomeImprovement       | 8566                |
| MusicalInstruments    | 88882               |
| OfficeProducts        | 149675              |
| Toys&Games            | 15867               |
| Grand Total           | 26802717            |

   - **Insight:**

     The Electronics category dominates customer engagement with over 15.7 million reviews, indicating its position as the most popular and actively reviewd productt, accounting for nearly 59% of all reviews. Computers & Accessories and Home & Kitchen follow with 7.7 million and 2.9 million reviews respectively. In contrast, categories like Health & Personal Care, Toys & Games, and Car & Motorbike have significantly fewer reviews, indicating either lower customer interaction or limited product listings in those segments.


4.  Which products have the highest average ratings?

    - **Methodology:** Product name was placed in the 'row field' while Rating  was placec in the 'values field' summarized as average of values.
  
    - **Result:** from the table it was observed that several products stood out with exceptionally high average ratings with highest average rating of 4.80. This indicates strong customer stifaction and positive product experiences for the specific products.
 
5.   What is the average actual price vs the discounted price by category?

   - **Methodology:** Product category was placed in the 'row field' while Actual price and discounted price  was placed in the 'values field' summarized as average of values.
  
   - **Result:**

| Row Labels            | Average of actual_price | Average of discounted_price |
|-----------------------|-------------------------|-----------------------------|
| Car&Motorbike         | 4000                    | 2339                        |
| Computers&Accessories | 1683.623135             | 842.6503753                 |
| Electronics           | 10127.31179             | 5965.887833                 |
| Health&PersonalCare   | 1900                    | 899                         |
| Home&Kitchen          | 4162.073661             | 2330.615647                 |
| HomeImprovement       | 799                     | 337                         |
| MusicalInstruments    | 1347                    | 638                         |
| OfficeProducts        | 397.1935484             | 301.5806452                 |
| Toys&Games            | 150                     | 150                         |
| Grand Total           | 5444.990635             | 3125.310874                 |

    
6. Which products have the highest number of reviews?
 
   - **Methodology:** Product name was placed in the 'row field' while Rating  was placec in the 'values field' summarized as average of values.
  
    - **Result:**
  
      From the table result AmazonBasics Flexible Premium HDMI Cable (Black, 4K generated 853945 reviews making it the top 1 product with the hihest reviews.
   
7. How many products have a discount of 50% or more?

    - **Methodology:** Productdiscount percentage was placed in the 'row field' while product name  was placec in the 'values field' summarized as count of values.
  
    - **Result:**
  
      | Row Labels  | Count of Product Name |
|-------------|-----------------------|
| 50%         | 56                    |
| 51%         | 17                    |
| 52%         | 13                    |
| 53%         | 28                    |
| 54%         | 22                    |
| 55%         | 36                    |
| 56%         | 17                    |
| 57%         | 22                    |
| 58%         | 23                    |
| 59%         | 22                    |
| 60%         | 56                    |
| 61%         | 20                    |
| 62%         | 32                    |
| 63%         | 27                    |
| 64%         | 21                    |
| 65%         | 31                    |
| 66%         | 22                    |
| 67%         | 12                    |
| 68%         | 10                    |
| 69%         | 17                    |
| 70%         | 28                    |
| 71%         | 10                    |
| 72%         | 5                     |
| 73%         | 16                    |
| 74%         | 9                     |
| 75%         | 29                    |
| 76%         | 14                    |
| 77%         | 17                    |
| 78%         | 15                    |
| 79%         | 8                     |
| 80%         | 37                    |
| 81%         | 7                     |
| 82%         | 5                     |
| 83%         | 5                     |
| 84%         | 2                     |
| 85%         | 12                    |
| 86%         | 4                     |
| 87%         | 3                     |
| 88%         | 6                     |
| 89%         | 1                     |
| 90%         | 8                     |
| 91%         | 5                     |
| 94%         | 1                     |
| Grand Total | 751                   |

    
10. What is the distribution of product ratings (e.g., how many products are rated 3.0, 
4.0, etc.)? 
11. What is the total potential revenue (actual_price × rating_count) by category? 
12. What is the number of unique products per price range bucket (e.g., <₹200, 
₹200–₹500, >₹500)? 
13. How does the rating relate to the level of discount? 
14. How many products have fewer than 1,000 reviews? 
15. Which categories have products with the highest discounts? 
16. Identify the top 5 products in terms of rating and number of reviews combined.
