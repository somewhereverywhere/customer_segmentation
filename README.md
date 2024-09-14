

# Customer Segmentation and Marketing Strategy Enhancement on Superstore Marketing Data

## Project Overview
This project focuses on customer segmentation using the Superstore dataset, with the goal of increasing sales and developing targeted marketing strategies. By segmenting customers based on their purchasing behaviors, this project aims to enhance customer engagement and business revenue. Additionally, probability analysis is conducted to assign probability distributions to different products and calculate expected values for improved decision-making.

## Objectives
- Perform customer segmentation to identify key customer groups.
- Use segmentation results to inform and improve marketing strategies.
- Apply probability distributions to predict customer behavior.
- Calculate expected values 

## Dataset
- **Superstore Marketing Data**
- **Features**: Id,Year_Birth,Education,Marital_Status,Recency,MntWines,MntFruits,MntMeatProducts and more.

## Steps
1. **Data Preprocessing**:  
   - Handle missing values and clean the dataset.
   - Feature engineering to extract relevant information (e.g., total spend, frequency).
   
2. **Customer Segmentation**:
   - Applied K-Means clustering algorithm to group customers based on key features like sales, frequency, and region.
   - Evaluated the number of clusters using the **elbow method** to determine optimal segmentation.

3. **Probability Distribution and Expected Value**:
   - Assigned probability distributions to different products to predict future purchasing behavior.
   - Calculated expected values for each to identify high-value customers.

4. **Marketing Strategy Enhancement**:
   - Proposed targeted marketing strategies based on the insights from segmentation and probability analysis to optimize sales and customer retention.

## Results
- Identified 3 distinct customer segments with varying behaviors and preferences.
- Low Income, Occasional Buyers is the largest segment, with 1025 customers
- This could indicate that a significant portion of the customer base is more price-sensitive and possibly less loyal, making them more likely to respond to promotions, discounts, and marketing efforts aimed at 
  increasing purchase frequency
## Tools & Technologies
- **Python**: Data processing and analysis.
- **Pandas**: Data wrangling and preprocessing.
- **Scikit-learn**: K-Means clustering and probability modeling.
- **Matplotlib/Seaborn**: Data visualization and plotting.
- **Google Colab**: Project execution and code demonstration.

## Future Enhancements
- Implement additional clustering techniques (e.g., DBSCAN) to compare segmentation results.
- Use more advanced models like **RFM (Recency, Frequency, Monetary)** analysis to refine the customer segments.
- Integrate real-time data analysis for more dynamic customer segmentation and marketing.

## Conclusion
This project successfully applied customer segmentation and probability analysis to enhance marketing strategies on a small dataset. The insights gained from this analysis can be leveraged to increase sales and improve customer engagement, demonstrating the power of data-driven decision-making.
