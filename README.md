# Customer-Segmentation-Using-KMeans
# Customer Segmentation Using K-Means

## Author
**Saloni Kaushal**

## Project Overview

Customer segmentation is a marketing strategy used to divide customers into different groups based on their purchasing behavior.

This project uses **RFM (Recency, Frequency, Monetary) Analysis** and **K-Means Clustering** to identify customer segments from retail transaction data. These segments help businesses understand customer behavior and create targeted marketing campaign.

## Objectives

- Analyze retail customer purchasing behavior.
- Calculate RFM metrics for each customer.
- Apply K-Means Clustering to group similar customers.
- Visualize customer segments.
- Generate insights for targeted marketing.
## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
## Dataset

The project uses a retail customer transaction dataset containing:

- Customer ID
- Invoice Number
- Purchase Date
- Quantity Purchased
- Unit Price

## Methodology

### 1. Data Collection
The retail customer dataset was loaded into Python for analysis.

### 2. Data Cleaning
- Removed missing values.
- Removed invalid transactions.
- Removed negative quantities and prices.

### 3. Feature Engineering
A new feature called **Total Amount** was created:

Total Amount = Quantity × Unit Price

### 4. RFM Analysis

#### Recency (R)
Number of days since the customer's last purchase.

#### Frequency (F)
Number of purchases made by the customer.

#### Monetary (M)
Total amount spent by the customer.

### 5. Feature Scaling
StandardScaler was used to normalize the RFM values.

### 6. K-Means Clustering
Customers were grouped into clusters based on their RFM characteristics.

### 7. Visualization
Customer segments were visualized using scatter plots.

## Results

The clustering process successfully divided customers into multiple segments such as:

- High-Value Customers
- Loyal Customers
- Regular Customers
- At-Risk Customers

These segments can be used to improve marketing effectiveness and customer retention.

## Project Outcomes

- Identified customer groups based on purchasing patterns.
- Performed customer behavior analysis.
- Applied machine learning for segmentation.
- Generated actionable business insights.

## Future Improvements

- Use advanced clustering algorithms.
- Build an interactive dashboard.
- Deploy the project using Streamlit.
- Perform customer lifetime value analysis.

## Conclusion

Customer segmentation helps businesses better understand their customers and design personalized marketing strategies. Using RFM Analysis and K-Means Clustering, this project successfully identified meaningful customer groups from retail transaction data.

---

## Thank You
