# Marketing-Campaign-Analysis
---

## Table of contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Dictionary](#data-dictionary)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Insights](#insights)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- ---


### Project Overview
The project aims to provide insights into the effectiveness of marketing campaigns and track complaints by analysing customer demographics, behaviours and Preferences.

https://tinyurl.com/c6bhsazx

![image](https://github.com/user-attachments/assets/a3d3d6d0-bdea-4dcb-9228-b679034c766a)

---

### Data Sources
The dataset used for this analysis is the "Marketing_campaign.csv" containing detailed information about the customer.

---
### Tools
- Excel - Data Cleaning
- PowerBi- Creating Reports
- Canva - Designing Backgrounds
- Powerpoint- Designing
---
### Data Dictionary

- ID: Customer's unique identifier.
- Year_Birth: Customer's birth year.
- Education: Customer's education level
- Marital_Status: Customer's marital status
- Income: Customer's yearly household income
- Kidhome: Number of children in customer's household
- Teenhome: Number of teenagers in customer's household
- Dt_Customer: Date of customer's enrollment with the company
- Recency: Number of days since customer's last purchase
- Complain: 1 if the customer complained in the last 2 years, 0 otherwise
- MntWines: Amount spent on wine in last 2 years
- MntFruits: Amount spent on fruits in last 2 years
- MntMeatProducts: Amount spent on meat in last 2 years
- MntFishProducts: Amount spent on fish in last 2 years
- MntSweetProducts: Amount spent on sweets in last 2 years
- MntGoldProds: Amount spent on gold in last 2 years
- NumDealsPurchases: Number of purchases made with a discount
- AcceptedCmp1: 1 if customer accepted the offer in the 1st campaign, 0 otherwise
- AcceptedCmp2: 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
- AcceptedCmp3: 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
- AcceptedCmp4: 1 if customer accepted the offer in the 4th campaign, 0 otherwise
- AcceptedCmp5: 1 if customer accepted the offer in the 5th campaign, 0 otherwise
- Response: 1 if customer accepted the offer in the last campaign, 0 otherwise
- NumWebPurchases: Number of purchases made through the company’s website
- NumCatalogPurchases: Number of purchases made using a catalogue
- NumStorePurchases: Number of purchases made directly in stores
- NumWebVisitsMonth: Number of visits to company’s website in the last month
---
### Data Cleaning
In the data cleaning and preparation phase, the following task were  performed:
- Data loading and inspection.
- Handling missing values.
- Outlier detection
- Data cleaning and formatting.
- Data Modelling.

  ![Modelling](https://github.com/user-attachments/assets/7c747b94-7c10-4c4c-b89a-bdbbc67805df)

---
 ### Exploratory Data Analysis
 The EDA involved exploring the dataset mto anser key questions such as:
 1. Which customer segments (age, marital status, kids, income, education) are most likely to accept the marketing campaigns?
 2. Is there a correlation between income and expenses?
 3. What is the relationship between age and product preferences, and how can we use this information to tailor future campaigns?
 4. which customer segments (age, marital status, kids, income, education) are most likely to complain the most.
 5. What patterns can we observe in customer behavior across different campaigns, and how can we use these insights to forecast future campaign success?
---
### Insights
1. 50.31 % of their customers are in the Graduate category of Education while 2.41% have Basic Education
2. There is a positive correlation betweern Middle income earners and expenses.
3. Married and People living together are making most of the expenses
4. Customers in age grade 41-60 yrs and 61years and above are buying most of the wines and meats
5. Customers in age grade 41-60 yrs preferes stores purchases and they have the highest web visits
6. Most of the complaints are coming from the Graduates, Married, low income earners and those in 60years and above age agroup.
7. Customers most likely to acccept Campaigns are the Graduates, Married,Middle income earners and those in age group 41-60 years of age.
---
### Recommendations
1. Since over half of the customer base (50.31%) has a graduate-level education, tailor marketing messages to appeal to this group’s preferences for premium or specialized products. Highlight product quality, educational value, or sustainability to attract their attention.
2. Given the positive correlation between middle-income earners and expenses,the company should focus on creating special offers or loyalty programs that encourage repeat purchases. Emphasize affordability without compromising quality to maximize engagement with this segment.
3. Since Customers aged 41-60 and 61+ buy most of the wines and meats, the company should Consider crafting campaigns that feature premium wines and gourmet meats, specifically targeting this age group with personalized offers, particularly through in-store promotions and online channels.
4. Since this age group prefers in-store purchases and has the highest web visits, the company should focus on a seamless omnichannel strategy. Offer click-and-collect services, personalized discounts for in-store shopping, or incentives to drive store foot traffic.
---
### Limitations
1. Missing values were found in the income column and they were replaced by the median income value
2. Three(3) Outliers were identified in the age column during the data analysis; however, they were not addressed in the current analysis."
