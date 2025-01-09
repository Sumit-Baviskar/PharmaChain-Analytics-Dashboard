#  :chart_with_upwards_trend: **Pharmacy Supply Chain Dashboard (Excel Project)** :chart_with_upwards_trend:


# :paperclip: **Introduction :** 

The pharmaceutical supply chain is a critical component of the healthcare industry, ensuring the timely delivery of essential products such as medical equipment, consumables, and pharmaceuticals to customers. The provided dashboard offers a comprehensive overview of key business metrics, such as revenue trends, order priorities, profit margins, shipping costs, and product performance. These insights are vital for understanding operational efficiency, identifying growth opportunities, and addressing areas that require improvement.

The analysis reveals significant achievements, such as total revenue surpassing ₹2.9 million and a strong customer base of 3,347 across major regions like Maharashtra, Delhi, and Kolkata. However, challenges persist, including fluctuations in revenue over the years, high shipping costs, and uneven performance across products, regions, and sales representatives. By addressing these gaps and capitalizing on strengths, the company can enhance its profitability, expand its market presence, and establish a more efficient and scalable supply chain.

The following recommendations are designed to provide actionable strategies that leverage the company's current successes while addressing key challenges. These suggestions focus on optimizing operational costs, expanding market share, improving product mix profitability, enhancing team performance, and sustaining the impressive revenue growth seen in recent years.


# :green_book: **Purpose of the project :** :green_book:

The Pharma Supply Chain Dashboard Analysis was designed to provide a comprehensive view of the operational and financial performance of a pharmaceutical supply chain. The purpose of this project is to harness data visualization and analytics to support data-driven decision-making and optimize business processes.

This project aims to:

#### **1.Enhance Business Understanding:**
- Provide key stakeholders (e.g., executives, managers, and analysts) with clear and actionable insights into revenue trends, order priorities, shipping costs, product performance, and regional contributions.

#### **2.Identify Strengths and Opportunities:**
- Highlight high-performing products, regions, and sales representatives to replicate their success across other areas.

- Identify underperforming products and regions to explore growth opportunities and address challenges.

#### **3.Optimize Operational Efficiency:**
- Analyze shipping costs and order priorities to identify areas where cost efficiencies can be achieved without compromising service quality.

- Improve profit margins by focusing on high-performing product categories and streamlining processes for critical orders.

#### **4.Support Strategic Planning:**
- Offer data-backed recommendations to aid in the formulation of short-term and long-term strategies for revenue growth, cost reduction, and market expansion.
- Ensure alignment between operational performance and organizational goals.

#### **5.Enable Real-Time Monitoring:**
- Create an interactive and user-friendly dashboard for continuous monitoring of key performance indicators (KPIs), allowing quick responses to evolving market conditions and operational challenges.


The overarching goal is to help the organization make informed decisions to improve profitability, enhance customer satisfaction, and strengthen its competitive position in the pharmaceutical supply chain industry.



# :green_book: **Business Question:** :green_book:

#### **1. What is the total revenue generated across all years in the pharma supply chain?**

#### **2.  How many total orders have been processed?**

#### *3.  What is the overall profit margin achieved by the company?**

#### **4. What is the total cost incurred for shipping products?**

#### **5. How many customers are served in total?**

#### **6. How has the revenue trend varied from 2019 to 2024?**

#### **7. Which product category contributes the most to the revenue, and by what percentage?**

#### **8. Which order priority (Critical, High, Medium, Low) handles the highest quantity of orders?**

#### **9. Which state (Delhi, Kolkata, Maharashtra) has the largest share of customers, and how are they distributed?**

#### **10. What is the average shipping cost for different modes of transportation (Delivery Truck, Express Air, Regular Air)?**

#### **11. Which order priority yields the highest profit margin?**

#### **12. Which product container type (Jumbo Pack, Large Pack, Medium Pack, Small Pack) generates the highest profit margin?**

#### **13. Which state (Maharashtra, Kolkata, Delhi) has shown the highest revenue growth over the years?**

#### **14. What are the top 10 products generating the highest revenue, and what is their contribution?**

#### **15. Which medical sales representative has the highest total sales over the years?**


# :green_book: **Data Cleaning and Transformation Process :** :green_book:


![Screen Shot 2024-11-29 at 7 44 35 PM](https://github.com/user-attachments/assets/2489ee27-3bed-4de8-9740-9a6763e84bf5)


In the process of cleaning and transforming the dataset, several key steps were undertaken to ensure accuracy, consistency, and usability for analysis. The data cleaning and transformation activities focused on organizing the raw dataset, resolving inconsistencies, and enriching the data for meaningful insights. Below is an outline of the actions performed:

#### 1. **Standardizing Column Headers**:  
 - The raw data contained misaligned headers and unnamed columns, making it difficult to interpret the data. All column names were standardized for clarity and uniformity, ensuring a consistent naming convention.

#### 2. **Handling Missing and Redundant Data**:  
 - Rows and columns with missing or irrelevant data were identified and removed or filled with appropriate values where necessary. This step eliminated noise and enhanced the dataset's quality.

#### 3. **Reformatting Data**:  
   - Dates in the "Order Date" column were reformatted to a consistent format, improving readability and compatibility with analysis tools.  
   - Numerical fields such as "Cost Price," "Retail Price," and "Profit Margin" were standardized to ensure consistent decimal precision.

#### 4. **Deriving New Attributes**:  
- Additional columns such as "Order Year," "Order Quarter," and "Order Month" were derived from the "Order Date" column to facilitate time-based analysis. These attributes enable segmentation of data by specific time periods, enhancing trend analysis.

#### 5. **Correcting Inconsistencies**:  
 - Customer and address details were cleaned to remove formatting errors, such as extra spaces or inconsistent abbreviations, ensuring a uniform representation of textual data.

#### 6. **Validating Calculations**:  
 - Key financial metrics such as "Order Total," "Discount $," and "Total Cost" were recalculated and validated to ensure the accuracy of computations, correcting any discrepancies present in the raw data.

#### 7. **Removing Empty Rows and Columns**:  
 - Any rows or columns containing only `NaN` values or irrelevant data were removed to streamline the dataset and enhance its usability.

These transformations ensured that the dataset was clean, accurate, and structured in a manner that supports comprehensive analysis and decision-making.



# :paperclip: **Business Solution :**  


#### ☑️**1. What is the total revenue generated across all years in the pharma supply chain?**

- **Insights :** The total revenue generated is ₹2,932,881.34, reflecting the cumulative sales from all products and years.


----------------------------------------------------------------------------------------------------------------------------------------------



#### ☑️**2.  How many total orders have been processed?**

- **Insights :** With 88,201 orders processed, the volume reflects high operational activity. The business might explore whether efficiency or cost savings can improve with such a large order count.


----------------------------------------------------------------------------------------------------------------------------------------------




#### ☑️*3.  What is the overall profit margin achieved by the company?**
- **Insights :** A profit margin of ₹106,844.14 indicates that while the company is profitable, the profit percentage relative to revenue could be evaluated for improvement.

----------------------------------------------------------------------------------------------------------------------------------------------




#### ☑️**4. What is the total cost incurred for shipping products?**
- **Insights :** Shipping cost of ₹20,281.73 suggests that logistics is a notable expense. Exploring cost-effective shipping methods, especially for the highest-cost mode (Delivery Truck), might yield savings.

----------------------------------------------------------------------------------------------------------------------------------------------




#### ☑️**5. How many customers are served in total?**
- **Insights :** Serving 3,347 customers demonstrates a robust customer base. Strategies to retain existing customers and acquire new ones could further boost revenue.


----------------------------------------------------------------------------------------------------------------------------------------------


#### ☑️**6. How has the revenue trend varied from 2019 to 2024?**
- **Insights :**
  - **Revenue trends across years:**
    - 2019: Moderate revenue growth.
    - 2020-2022: A decline is observed in these years.
    - 2024: A significant spike in revenue, showing robust growth.

- **Recommendation :**
  - Conduct a root cause analysis of the revenue dip between 2020 and 2022. This may involve examining market conditions, competitive pressures, or operational inefficiencies. Based on the 2024 spike, identify strategies that contributed to the recovery, such as new product launches or market penetration, and replicate these in other underperforming years.

  - Additionally, focus on diversifying revenue sources across product categories and regions to reduce dependency on a few high-performing products or states.

----------------------------------------------------------------------------------------------------------------------------------------------


#### ☑️**7. Which product category contributes the most to the revenue, and by what percentage?**
- **Insights :** Pharmaceuticals contribute 43% of total revenue, making it the largest revenue driver, followed by Consumables (30%) and Medical Equipment (27%). This product distribution highlights the reliance on pharmaceuticals, but other categories also show growth potential.

- **Recommendation :** Continue investing in the pharmaceutical product line to maintain leadership in this segment. Simultaneously, allocate resources to grow the Medical Equipment and Consumables categories by introducing innovative products or marketing strategies to target specific customer needs. This balanced approach will help mitigate risks associated with over-dependence on a single category.


----------------------------------------------------------------------------------------------------------------------------------------------


#### ☑️**8. Which order priority (Critical, High, Medium, Low) handles the highest quantity of orders?**

- **Insights :**
  - Orders handled by priority:
    - Medium Priority: 32,628 (highest).
    - Low Priority: 23,776.
    - High Priority: 17,058.
    - Critical Priority: 14,739.

- **Recommendation :** Recommendation: Analyze the factors contributing to the lower performance of critical orders. This may involve assessing logistical challenges, cost structures, or operational bottlenecks in handling urgent orders. Consider offering premium pricing for critical orders to improve profitability while ensuring faster and more efficient fulfillment.


----------------------------------------------------------------------------------------------------------------------------------------------

#### ☑️**9. Which state (Delhi, Kolkata, Maharashtra) has the largest share of customers, and how are they distributed?**

- **Insights :**
  - Customer distribution is fairly even among Delhi (34%), Kolkata (34%), and Maharashtra (32%), indicating a balanced presence.
  - However, expanding in Maharashtra could equalize the market share.
   
----------------------------------------------------------------------------------------------------------------------------------------------


#### ☑️**10. What is the average shipping cost for different modes of transportation (Delivery Truck, Express Air, Regular Air)?**

- Average shipping costs by mode:
  - Delivery Truck: ₹38.46 (highest cost).
  - Express Air: ₹5.42.
  - Regular Air: ₹5.10 (lowest cost).

- Delivery Trucks are the most expensive shipping mode (₹38.46), which could be optimized. Express Air and Regular Air have similar, much lower costs, making them cost-efficient alternatives for certain shipments.


----------------------------------------------------------------------------------------------------------------------------------------------



#### ☑️**11. Which order priority yields the highest profit margin?**

- **Insights :**
     - Profit margins by order priority:
     - Low Priority: ₹52,375.08 (highest).
     - Medium Priority: ₹26,233.40.
     -  High Priority: ₹18,649.97.
     - Critical Priority: ₹9,585.69 (lowest).

- **Recommendation :** Analyze the factors contributing to the lower performance of critical orders. This may involve assessing logistical challenges, cost structures, or operational bottlenecks in handling urgent orders. Consider offering premium pricing for critical orders to improve profitability while ensuring faster and more efficient fulfillment.


----------------------------------------------------------------------------------------------------------------------------------------------


#### ☑️**12. What are the top 10 products generating the highest revenue, and what is their contribution?**

- **Insights :**

  - **Top revenue-generating products :**

    - Hazardous Waste Bags: ₹67,429.52.

    - Scalpel Blades: ₹64,620.36.

    - Fetal Dopplers: ₹48,524.88.

    - Blood Collection Bags: ₹43,644.98.

    - Splints: ₹42,875.99.

    - Forceps: ₹41,509.92.

    - Dental Chairs: ₹40,846.47.

    - Culture Media: ₹40,574.88.

    - First Aid Kits: ₹40,507.38.

    - Face Masks: ₹39,754.32.

- **Recommendation :** Diversify revenue streams by identifying and promoting potential high-growth products outside the top 10. Similarly, explore untapped markets or states to reduce dependency on Maharashtra. Conduct customer segmentation analysis to identify emerging needs and tailor product offerings to capture a broader market share.


# :green_book: **Dashboard :** :green_book:

![Screen Shot 2025-01-09 at 10 45 47 PM](https://github.com/user-attachments/assets/97acea19-ee10-492a-978a-0a534bd29519)


----------------------------------------------------------------------------------------------------------------------------------------------


# :green_book: **Final Recommendations :**:green_book: 

#### **1.Optimize Shipping and Order Fulfillment Costs :**
- Reduce reliance on high-cost delivery modes like Delivery Trucks by optimizing logistics routes and shifting lighter shipments to Regular Air. Address inefficiencies in handling critical orders by streamlining processes and introducing premium pricing to enhance profitability.

#### **2.Focus on High-Performing Products and Regions :**
- Expand sales efforts for top-performing products such as Hazardous Waste Bags and Scalpel Blades while identifying and promoting emerging high-demand products. Strengthen operations in Maharashtra, leveraging its growth momentum, and target Delhi for expansion to balance regional contributions.

#### **3.Enhance Profit Margins Through Product Strategy :**
- Drive sales of Jumbo Packs, which yield the highest profit margin, by offering incentives for bulk purchases. Simultaneously, leverage the unexpectedly strong performance of Small Packs through targeted marketing to niche customer segments.

#### **4.Boost Sales Team Performance :**
- Address disparities in sales performance by providing tailored training, reallocating resources, and implementing incentive programs. Regularly monitor representative performance and provide actionable feedback to underperforming team members.

#### **5.Capitalize on Recent Revenue Growth :**
- Investigate the key drivers behind the sharp revenue increase in 2024 and replicate these strategies across other underperforming years, product lines, or regions. Use predictive analytics to identify future growth opportunities and proactively allocate resources to sustain momentum.










# :paperclip: **Conclusion :** 

The analysis of the dashboard highlights both the strengths and challenges faced by the pharmaceutical supply chain business. With a total revenue exceeding ₹2.9 million and a well-distributed customer base, the company has demonstrated its ability to cater to a diverse market effectively. High-performing products like Hazardous Waste Bags and Scalpel Blades, coupled with Maharashtra's significant contribution to revenue, underscore the company's strong market positioning.

However, areas such as high shipping costs, underperformance in critical order priorities, and uneven sales representative contributions highlight opportunities for improvement. By implementing targeted strategies such as optimizing logistics, enhancing critical order fulfillment, and leveraging the growth momentum of high-performing products and regions, the company can achieve sustainable growth.

In conclusion, by addressing these challenges and strategically focusing on areas of opportunity, the company can strengthen its competitive advantage, improve profitability, and ensure consistent growth in an increasingly competitive market. The recommendations provided offer a roadmap for achieving these goals, laying the foundation for long-term success in the pharmaceutical supply chain industry.






