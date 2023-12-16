# Analyzing Real-World POS Data: Unveiling Consumer Behavior & Strategic Insights using SAS Software

The present work presents a comprehensive analysis of real sales data from company XYZ, using exploratory analysis as well as machine learning techniques such as RFM analysis (clustering), market basket analysis, and conducting predictions using a decision tree. The study leverages the capabilities of **SAS Viya & SAS EG** tools to extract valuable insights from the data and discover patterns and trends that can influence strategic decision-making.


[**Exploratory Analysis**](https://github.com/moraitis-alexandros/Analyzing-Real-World-POS-Data-Unveiling-Consumer-Behavior-and-Strategic-Insights-using-SAS-Software/blob/main/Exploratory-Analysis)

The Exploratory Data Analysis (EDA) encompassed a comprehensive investigation into sales dynamics, including detailed insights into sales levels across diverse product types. It delved into returns, calculating total monetary value and introducing the novel Loss Rate metric, shedding light on product inefficiencies impacting revenue. Analysis identified top-performing products per type, examined market share, mapped regional revenue distribution, and assessed supplier demand. Additionally, it explored variations in average basket size across weekdays, providing key insights into consumer behavior. The creation of new metrics like the Loss Rate enriched the analytical framework, empowering strategic decision-making for revenue optimization and operational enhancements at XYZ company.

[**RFM Analysis**](https://github.com/moraitis-alexandros/Analyzing-Real-World-POS-Data-Unveiling-Consumer-Behavior-and-Strategic-Insights-using-SAS-Software/blob/main/RFM-Analysis)

The enriched RFM analysis, segmented customers into four categories - Best (48.6%), First Timer (17.6%), Churner (28%), and Hibernating (19.7%). This segmentation, coupled with age-based clusters and new metrics like Weighted Churn Rate and Weighted Best Rate, pinpointed regions with high churners and concentrations of best customers. These insights paved the way for targeted strategies, emphasizing increasing the share of Best customers while addressing the challenge of high churn rates. Exploring potential correlations between churners and returns also provided actionable insights for product/service enhancements, contributing to XYZ company's refined targeting, retention, and satisfaction initiatives.

[**Market Basket Analysis**](https://github.com/moraitis-alexandros/Analyzing-Real-World-POS-Data-Unveiling-Consumer-Behavior-and-Strategic-Insights-using-SAS-Software/blob/main/Market-Basket-Analysis)

Identified pivotal products influencing sales, such as Hailstorm Steel Woods Set, Course Pro Umbrella, and Husky Rope 60, which collectively contributed to a substantial portion of total sales.

[**Decision Tree Analysis**](https://github.com/moraitis-alexandros/Analyzing-Real-World-POS-Data-Unveiling-Consumer-Behavior-and-Strategic-Insights-using-SAS-Software/blob/main/Decision-Tree-Analysis)

Predicted customer category 97 purchases to strategically allocate discount coupons, significantly enhancing buyer predictions by 2,9758 times compared to a basic model.

*The project was part of my final SAS Joint Certificate Report*

## References





## Exploratory Data Analysis Insights:

## Objective: 

The primary aim was to conduct an in-depth exploratory data analysis (EDA) to decipher supplier demand, revenue trends, and factors influencing consumer preferences in product selection.

## Tools Used

SAS EG

SAS Viya

## Dataset Overview:

*Invoice:* Contains 24,214 unique transactions (baskets).

*Basket:* Links 418,771 transactions (baskets) to the respective products.

*Customers:* Includes data on 10,000 unique customers.

*Products:* Encompasses details of 144 unique products.

## Key Highlights

*Age Range Transformation:* To enhance the analysis of age, it would be beneficial to categorize ages into specific age brackets (Very Young, Young, Middle Age, Mature, Old, Very Old). With this categorization, 
a more organized result emerges: Middle age customers represent 37.09%, followed by the Young group at 30.21%, while the Very Young group comprises 18.20%, showing a clearer breakdown of age segments.

*Top Product per Product Type & Market Share:* The analysis focuses on identifying the top-selling product within each category and its market share compared to other products within the same category. The results reveal significant products like Hailstorm Steel Woods Set, Course Pro Umbrella, and Hailstorm Steer Irons, each occupying a quarter of sales (25% - 26%) in their respective categories. Moreover, the Husky Rope 60 Blue Steel Max Putter dominates its category with a substantial 34% market share. Notably, within categories like watches and eyewear, while the top products hold a small share (8% and 6% respectively), the categories themselves constitute a significant portion of total sales 
(9% and 11% respectively), indicating broader diversity in those categories despite individual product dominance. This analysis provides insights into both product-specific and category-wide market dynamics.

*Maps Creation and integration with other Datasets:* Analyzed loss rates by connecting demographic density, observed significant loss rates in specific areas, and created a Tile Chart to depict these relationships.
Generated maps in Viya using longitude and latitude data from the Query_for_loss_Perc table, establishing a Geo-Hierarchy based on Country and Region levels for spatial analysis.

## In-depth Insights:

#### Sales Patterns:

- **Weekday Sales Trends**: Increased sales observed from Tuesday to Friday, indicating higher sales in receipts issued, total products sold, and overall sales value.

- **Friday Surges**: Potential consumer purchases aimed at utilizing leisure time over the weekend, attributed to the store selling various hobby-related items.

- **Lowest Sales Days**: Monday and Saturday, likely due to:

  - **Monday Effect**: Individuals starting their workweek, less time for online shopping.
 
  - **Weekend Activities**: Saturdays associated with outdoor activities and family time, reducing time for online shopping.

#### Consumer Behavior by Weekday:

- **Average Basket Size per Weekday**: Notable observation: Friday, Saturday, and Tuesday have the highest average basket sizes. 

- **Saturday's Impact**: Despite lower sales counts, products sold on Saturdays contribute significantly more to the overall revenue due to higher average basket sizes.

### Revenue Insights by Product Origin & Supplier:

Turkish Product Revenue: Lower total revenues indicate potential consumer disinterest or lower pricing. Unlike Chinese products, Turkish items lack consumer preference despite similar pricing.

Indian Product Lead: Despite lower individual values compared to similar US-made items, Indian products attract consumers due to a better quantity-price balance, securing the top position in revenue.

US Product Appeal: Despite higher unit values compared to counterparts, US products rank second in revenue, favored for their quality-price equilibrium.

### Operational Suggestions:

#### Operational Recommendations:

- **Targeted Campaigns**: Suggested focused email marketing campaigns on Mondays and especially Saturdays, capitalizing on consumer interest and high-value products.

- **Increased Sales Strategy**: Proposed efforts to boost sales on these specific days through targeting

- **Minimize Turkish Offerings:** Consider reducing Turkish products due to potential consumer mismatch.
  
- **Highlight Indian Selections:** Focus on Indian products for customers seeking multiple reasonably priced items, especially during promotions.

- **Promote US Merchandise:** Emphasize US products for consumers valuing quality at a reasonable price. This aligns with discerning the best customer segments through subsequent RFM analysis.





