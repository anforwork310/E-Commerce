# E-Commerce-Project

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
<img width="873" height="256" alt="image" src="https://github.com/user-attachments/assets/56432c8a-4408-42d3-8344-1c1f5f3aaba2" />

- Query results
<img width="1234" height="400" alt="image" src="https://github.com/user-attachments/assets/5664c6af-1b72-4e0e-a28c-05a35e6f5789" />

### **Question 2:  Bounce rate per traffic source in July 2017 (Bounce_rate = num_bounce/total_visit) (order by total_visit DESC)**

- SQL code
<img width="951" height="269" alt="image" src="https://github.com/user-attachments/assets/4db60346-a382-46ef-bdbe-603c95420c9f" />

- Query results
<img width="1239" height="661" alt="image" src="https://github.com/user-attachments/assets/337b0245-4641-4116-96f2-219d64711574" />

### **Question 3: Revenue by traffic source by week, by month in June 2017**
- SQL code
<img width="954" height="695" alt="image" src="https://github.com/user-attachments/assets/2e67ca13-4983-478c-adb4-76c038d61b64" />

- Query results
<img width="1302" height="734" alt="image" src="https://github.com/user-attachments/assets/d5cf0692-7963-4452-bec1-67d61c93f9a0" />

### **Question 4: Average number of pageviews by purchaser type (purchasers vs non-purchasers) in June, July 2017.**
- SQL code
<img width="736" height="640" alt="image" src="https://github.com/user-attachments/assets/fa6b4511-ff66-4c32-bd99-79bd59edd5ac" />

- Query results
<img width="970" height="186" alt="image" src="https://github.com/user-attachments/assets/ba27654b-1f97-46df-97b1-3ff3e8816dde" />

### **Question 5: Average number of transactions per user that made a purchase in July 2017.**
- SQL code
<img width="813" height="197" alt="image" src="https://github.com/user-attachments/assets/ea7b0b5e-ecfb-4b71-b606-2cf45f2ab762" />

- Query results
<img width="935" height="173" alt="image" src="https://github.com/user-attachments/assets/a3f53957-a4cb-4d0c-8fcf-cfe7d0a782f2" />

### **Question 6: Average amount of money spent per session. Only include purchaser data in July 2017.**
- SQL code
<img width="773" height="188" alt="image" src="https://github.com/user-attachments/assets/e4a11d82-f1d7-4fb5-b9d8-b93dc72f49ed" />

- Query results
<img width="955" height="158" alt="image" src="https://github.com/user-attachments/assets/403166e8-1601-414d-844c-66ccb481cecb" />

### **Question 7: Other products purchased by customers who purchased product "YouTube Men's Vintage Henley" in July 2017. Output should show product name and the quantity was ordered.**
- SQL code
<img width="897" height="405" alt="image" src="https://github.com/user-attachments/assets/53844c95-81f0-4328-ae05-5aba3e3009d2" />

- Query results
<img width="806" height="778" alt="image" src="https://github.com/user-attachments/assets/4f803d3c-5584-454e-8197-87896f62aba2" />

### **Question 8: Calculate cohort map from product view to addtocart to purchase in Jan, Feb and March 2017.**
- SQL code
<img width="712" height="882" alt="image" src="https://github.com/user-attachments/assets/851160c9-02d2-4143-926e-88f0ef5810e7" />

- Query results
<img width="944" height="202" alt="image" src="https://github.com/user-attachments/assets/62c0c589-688d-43ed-a600-709638727a86" />

## V. CONCLUSION
- This project demonstrates the power of SQL and BigQuery in analyzing large-scale marketing datasets.
- Insights gained include patterns in traffic sources, user engagement, and purchase behavior.
- Future work will focus on data visualization and business storytelling to communicate these findings more effectively.






