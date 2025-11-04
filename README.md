# E-Commerce

## I. OVERVIEW
- This project explores an **eCommerce dataset** using **SQL on Google BigQuery**. The dataset is based on the **Google Analytics public dataset** and contains information about user sessions, traffic sources, transactions, and revenue data from an eCommerce website.
- The objective of this project is to analyze **user engagement and purchasing behavior** through various SQL queries and to generate meaningful insights for business decision-making.

## II. OBECJECTIVES
- [Google Cloud Platform account](https://cloud.google.com/)
- Project created on Google Cloud Platform
- [Google BigQuery API](https://cloud.google.com/bigquery/docs) enabled
- SQL query editor or IDE (e.g., BigQuery Console)

## III. DATASET ACCESS
The eCommerce dataset is stored in a **public Google BigQuery dataset**.
To access it:
1. Log in to your Google Cloud Platform account and create a new project.  
2. Navigate to **BigQuery Console** and select your project.  
3. In the navigation panel, click **Add Data → Search a project**.  
4. Enter the project ID: 
5. Click on the `ga_sessions_` table to explore the schema.

## VI. EXPLORING THE DATASET

In this project, I will write 08 query in Bigquery base on Google Analytics dataset.

### **Question 1: Calculate total visit, pageview, transaction for Jan, Feb, March 2017**
- SQL code
<img width="562" height="161" alt="image" src="https://github.com/user-attachments/assets/58bad818-3138-48ca-bae2-fb4fe7b69a05" />

- Query results
<img width="857" height="220" alt="image" src="https://github.com/user-attachments/assets/2884461e-c4f9-4ea1-8a79-f265374c09c9" />

### **Question 2:  Bounce rate per traffic source in July 2017 (Bounce_rate = num_bounce/total_visit) (order by total_visit DESC)**
- SQL code
<img width="587" height="158" alt="image" src="https://github.com/user-attachments/assets/02595a98-ae56-4f15-bf67-422482315ff8" />

- Query results
<img width="849" height="640" alt="image" src="https://github.com/user-attachments/assets/978a6081-1ac9-410a-b9b3-744c7a3dbc91" />

### **Question 3: Revenue by traffic source by week, by month in June 2017**
- SQL code
<img width="590" height="431" alt="image" src="https://github.com/user-attachments/assets/b8d6cb22-b13c-4b94-b513-8a6ea0996ffa" />

- Query results
<img width="945" height="512" alt="image" src="https://github.com/user-attachments/assets/d4ed9d0a-4c14-4aee-aed3-037fffb56967" />

### **Question 4: Average number of pageviews by purchaser type (purchasers vs non-purchasers) in June, July 2017.**
- SQL code
<img width="686" height="632" alt="image" src="https://github.com/user-attachments/assets/345d2419-a2a3-4dee-82fa-8321b9f4ee0c" />

- Query results
<img width="951" height="200" alt="image" src="https://github.com/user-attachments/assets/7ac5181a-09a4-4bbb-ad02-e32b0c75ab1b" />

### **Question 5: Average number of transactions per user that made a purchase in July 2017.**
- SQL code
<img width="781" height="185" alt="image" src="https://github.com/user-attachments/assets/c5b35c88-e6c6-4702-9da2-b85f42a47be8" />

- Query results
<img width="944" height="168" alt="image" src="https://github.com/user-attachments/assets/71b41e47-5745-49f9-be5b-abdf1670d685" />

### **Question 6: Average amount of money spent per session. Only include purchaser data in July 2017.**
- SQL code
<img width="803" height="180" alt="image" src="https://github.com/user-attachments/assets/4d9d8f35-f1d4-434b-9e85-f3ec402ef95d" />

- Query results
<img width="943" height="150" alt="image" src="https://github.com/user-attachments/assets/e3205b4f-ead5-4c21-a592-1c4268c9d666" />

### **Question 7: Other products purchased by customers who purchased product "YouTube Men's Vintage Henley" in July 2017. Output should show product name and the quantity was ordered.**
- SQL code
<img width="856" height="414" alt="image" src="https://github.com/user-attachments/assets/0ad24ccf-39c1-4bd8-8b03-4edc6994595b" />

- Query results
<img width="939" height="556" alt="image" src="https://github.com/user-attachments/assets/a9503c9c-2a56-4a39-a62b-7a9d14fe70b7" />

### **Question 8: Calculate cohort map from product view to addtocart to purchase in Jan, Feb and March 2017.**
- SQL code
<img width="710" height="881" alt="image" src="https://github.com/user-attachments/assets/1f378ecc-52d0-4a1e-baa5-d824d8ff042f" />

- Query results
<img width="941" height="246" alt="image" src="https://github.com/user-attachments/assets/f778edb3-7e71-40c6-b899-0ad518b9841a" />

## V. CONCLUSION
- This project demonstrates the power of SQL and BigQuery in analyzing large-scale marketing datasets.
- Insights gained include patterns in traffic sources, user engagement, and purchase behavior.
- Future work will focus on data visualization and business storytelling to communicate these findings more effectively.






