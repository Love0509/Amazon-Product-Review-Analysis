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
  
## 3. Tools Used
  - Microsoft Excel
  - Pivot Tables
  - Excel Dashbard
 
## 4. Task Analysis and key insights
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

   - **Insight:** The Electronics category dominates customer engagement with over 15.7 million reviews, indicating its position as the most popular and actively reviewd productt, accounting for nearly 59% of all reviews. Computers & Accessories and Home & Kitchen follow with 7.7 million and 2.9 million reviews respectively. In contrast, categories like Health & Personal Care, Toys & Games, and Car & Motorbike have significantly fewer reviews, indicating either lower customer interaction or limited product listings in those segments.


4.  Which products have the highest average ratings?

    - **Methodology:** Product name was placed in the 'row field' while Rating  was placec in the 'values field' summarized as average of values.
  
    - **Result:** from the table it was observed that several products stood out with exceptionally high average ratings with highest average rating of 4.80. This indicates strong customer stifaction and positive product experiences for the specific products.
 
5.   What is the average actual price vs the discounted price by category?

   - **Methodology:** Product category was placed in the 'row field' while Actual price and discounted price  was placed in the 'values field' summarized as average of values.
    
6. Which products have the highest number of reviews?
 
   - **Methodology:** Product name was placed in the 'row field' while Rating  was placec in the 'values field' summarized as average of values.
  
    - **Insight:** From the table result AmazonBasics Flexible Premium HDMI Cable (Black, 4K generated 853945 reviews making it the top 1 product with the hihest reviews.
   
7. How many products have a discount of 50% or more?

    - **Methodology:** Productdiscount percentage was placed in the 'row field' while product name  was placec in the 'values field' summarized as count of values.

   - **Insight:** A total of 751 products have a discount of 50% or more, indicating that deep discounting is a common pricing strategy in the dataset. The most frequent discount levels are 50% and 60%, each applied to 56 products, suggesting those are popular thresholds used to attract buyers while maintaining margin control.
  
    
8. What is the distribution of product ratings (e.g., how many products are rated 3.0, 
4.0, etc.)?

 - **Insight:** The result suggests that most products are rated favorably, with a significant majority receiving above-average ratings, likely indicating strong customer satisfaction or rating inflation.
    
9. What is the total potential revenue (actual_price × rating_count) by category?
  - **Methodology:** A calculated column was created as a new column called potential revenue using the formula **'actual_price * rating count**.

- **Insight:** From the result, Electronics accounts for over ₦98 billion in potential revenue, making up the bulk of total sales value. Computers & Accessories and Home & Kitchen follow with ₦12.7B and ₦10.5B respectively. Other categories contribute relatively little, indicating that tech and home products drive the most revenue in this dataset.

  
10. What is the number of unique products per price range bucket (e.g., <₹200, 
₹200–₹500, >₹500)?

  - **Methodology:** A Calculated column was created using the formula: =IF(actual_price<200,"<₹200",IF(actual_price<=500,"₹200–₹500",">₹500"))

  - **Insight:** Most products (61%) are priced above ₹500, while only 14% fall below ₹200. This shows a strong focus on premium-priced items in the catalog.
    
11. How does the rating relate to the level of discount?
  
12. How many products have fewer than 1,000 reviews?
 
   - **Result:** Out of all products in the dataset, 326 products have received fewer than 1,000 reviews.
   
13. Which categories have products with the highest discounts?
    - **Result:** Electronics, Computers & Accessories, and Home & Kitchen have the highest number of discounted products, with 526, 453, and 448 items respectively. 
     
14. Identify the top 5 products in terms of rating and number of reviews combined.
    
 ## 5. Poject files
 -AMAZON CASE STUDY - Contains:
   - Cleaned data
   - Pivot table Analysis
   - Calculated columns
   - Excel Dashboardwith charts.

 ## 6. Contributor
 Johnson lovina 
 DSA Data Analyst in Training
 
