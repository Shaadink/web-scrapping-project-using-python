<p align="center">
  <h1 align="center"> 📱 Flipkart Mobile Market Intelligence Project </h1>
  <img src="https://github.com/Shaadink/web-scrapping-project-using-python/blob/main/webscrapping%20background%20picture.png" width="850"/>
</p>

## 🌟 Project Summary
This project demonstrates a complete, end-to-end **data science pipeline** focused on market intelligence within the e-commerce sector.  
It involves building a robust web scraper to gather product data from **Flipkart**, followed by rigorous **data cleaning**, **processing**, and **visual analysis** to derive **actionable market insights**.

**Skills Demonstrated:**  
`Web Scraping (BeautifulSoup, Requests)` • `Data Engineering (Pandas for ETL)` • `Data Visualization (Seaborn, Matplotlib)` • `Defensive Programming`

---

##  Key Objectives & Accomplishments

| **Objective** | **Description & Technical Achievement** |
|----------------|------------------------------------------|
| **Robust Scraping Engine** | Built a Python script that successfully navigates and extracts data across 10 sequential search result pages on Flipkart, demonstrating proficiency in handling dynamic URLs and HTML structure. |
| **ETL & Data Cleaning** | Implemented advanced Pandas transformations to convert raw string data (e.g., ₹44,999 and 4.6★) into clean, usable numeric formats. Ensured data integrity by aligning arrays and handling missing values (N/A) systematically. |
| **Market Analysis** | Performed quantitative analysis to understand the distribution of customer ratings, correlation between price and satisfaction, and competitive positioning of high-value products.
---

##  Core Technologies

| **Category** | **Tool** | **Application in Project** |
|---------------|-----------|------------------------------|
| **Programming** | Python 3 | Core language used for all scripting and analysis. |
| **Web Scraping** | BeautifulSoup | Efficiently parsed and traversed the complex HTML DOM to target specific product details. |
|  | Requests | Managed secure, time-out protected HTTP connections to the target site. |
| **Data Processing** | Pandas | Used for DataFrame creation, data type coercion, string manipulation (regex cleaning), and missing data imputation/handling. |
| **Visualization** | Seaborn / Matplotlib | Generated insightful charts (Histogram, Bar Plot, Scatter Plot) to communicate findings clearly. |

---

##  Data-Driven Insights

###  High Customer Satisfaction is Standard  
The **Distribution of Mobile Ratings** histogram showed that the majority of phones are highly rated, mostly clustered between **4.3 and 4.6 stars**.  
 This indicates a **mature and competitive market** where poor-quality products are quickly penalized.

###  Price is Not a Rating Guarantee  
The **Price vs. Ratings** scatter plot revealed **no direct positive correlation** between phone price and customer rating.  
 Consumers find **high-rated value phones** at all price levels — challenging the belief that “higher price = higher satisfaction.”
###  Market Discrepancies  
The **Top 10 Most Expensive Mobiles** bar chart highlighted anomalies — several phones listed above ₹50,000 (up to ₹1,20,000).  
 This suggests **dynamic pricing issues** or **data leakage** in Flipkart’s listings.

---

