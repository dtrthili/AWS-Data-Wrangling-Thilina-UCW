# AWS-Data-Wrangling-Thilina-UCW

**Project Description:**

Data Wrangling on Review Panel - UCE Academic Program Review

**Project Title:**

Enhanced Review Panel List: Data Wrangling

**Objective:**

The primary goal of this project is to perform data wrangling to prepare a robust dataset for review panel list for UCW Academic department. By cleaning, transforming, and consolidating data from various sources, the project aims to enhance the accuracy and usability of review panel data for subsequent analysis and reporting.

**Background:**

UCW Acedemic department has a review panel who review the programs in every 06 months. However, this data is often inconsistent, incomplete, or fragmented, making it challenging to derive meaningful insights. Effective data wrangling will facilitate better decision-making and more targeted marketing strategies.

https://www.ucanwest.ca/wp-content/uploads/2023/06/UCW-Policy-5001-Program-Review-2023-06-01.pdf


**Dataset:**

The Review Panel dataset consists of information such as:

• Panel-Id: Unique identifier for each reviewer

• Reviewer-Name: Name of the reviewer

• Field-of-Expert: Reviewer's field

• Role: Role with in the review panel (Member/Chair)

• Review-Date: Date of the review

• Feedback-Given: Submitted the feedback or not

• Expenses-Reimbursed: Reimbursed the expenses or not.

**Methodology:**

**1- Data Collection and Preparation:**

o Since I do not have the permission to get the review panel list of UCW, I have generated sample records (50 records)

![image](https://github.com/user-attachments/assets/8c9b0874-68f9-46a2-a397-7cf1fea29f0f)
 

**2- Data Assessment:**

![image](https://github.com/user-attachments/assets/7c5bad68-3024-4782-9376-1ba436b83e15)

Conduct an initial assessment of the data quality to identify issues such as missing values, duplicates, and inconsistencies across this dataset. Document data types, formats, and any discrepancies. I used profiling in AWS.


**3- Data Cleaning:**

![image](https://github.com/user-attachments/assets/27396032-a57c-4632-a430-a0fa40e5dbcc)

Address missing values through appropriate methods (e.g., imputation or exclusion) based on their significance and context. Remove duplicate records and correct inconsistencies in data formats (e.g., date formats, naming conventions). Normalize categorical variables to ensure consistency across datasets (e.g., standardizing Report Submitted status as "active" "inactive" ).


**4- Data Transformation:**

Perform data type conversions to ensure that all fields are in suitable formats for analysis (e.g., converting strings to datetime objects).

![image](https://github.com/user-attachments/assets/d289a713-714c-48da-bb84-2965fc928138)

 

**Conclusion:**

o Generated reliabile cleaned outputs for any business purposes.

o Tools and Technologies:

• AWS - Amazon S3 / AWS Data Brew  

This data wrangling project aims to establish a high-quality dataset that enables ucw to conduct effective review panel and driving overall business growth.
