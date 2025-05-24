# e_commerce_project

## eCommerce Business Analytics Project

#### https://docs.google.com/spreadsheets/d/1STtKsIKnq6rtUqRz_3mxyvazWUmho_WUvItbJ8K77z4/edit?usp=sharing

This project discusses the funnel and conversion metrics and retention rates for an eCommerce company

### Project Overview
This project contains 8 sheets:
1. Table of Contents
2. Executive Summary
3. Conversion Funnel sheet
4. Retention Rates sheet
5. Cohort Analysis sheet
6. First purchase sheet
7. Purchase Activity sheet
8. Raw user data sheet

## Sheet Descriptions and Screenshots

#### Table of Contents
This sheet is to show the table of contents of this project along with one sentence summaries of each sheet

![Screenshot 2025-01-21 143106](https://github.com/user-attachments/assets/ff96c21a-c6d5-4617-b50e-de887b464543)

#### Executive Summary
![Executive Summary sheet](https://github.com/user-attachments/assets/6e87c3f8-a623-457a-b9a4-e072f7d9c075)
1. **Conversion Funnel** - Of all users, only 29% make it to the shopping cart page, and only 10% of those make it the payment page
2. **Retention Rates** - Those that made their first purchase in 09-2020 had the most retention rates across all groups
- For the raw data, I only focused on users that made purchases. I then determined when the date of their first purchase was. 
I then converted that into a date and year and wrote a DATEDIF formula to find how many months' difference there was between the event date and the first payment date to start my cohort analysis.
- This table was calculated by first determining the total number of unique users that viewed the site, went to the shopping cart, and made it to the payment screen. 
I calculated the conversion between those 3 variables and the percentage of those that made it to the next step
- This table was calcuated using cohorts that only made purchases. I organized them based on how many months since their last event was their first purchase. 

#### Conversion Funnel Sheet
![conversion rates](https://github.com/user-attachments/assets/1f4c6739-63ae-4ac2-a25b-6a230ef19eea)
I used aggregate functions to find that only 29% of all users made it to the shopping cart page. And out of that 29%, only 10^ made it to the payment page.

#### Retention Rates Sheet
![retention rates sheet](https://github.com/user-attachments/assets/42041dad-2e5f-4fe1-9053-cbbb1956b9d1)
I found that those users who first purchased an item in 09/2020 had the most retention across all cohort groups.

#### Cohort Analysis Sheet
![cohort analysis](https://github.com/user-attachments/assets/8107718b-8762-4ad5-84db-e35ec4c3cd7f)
This sheet shows the analysis of unique user IDs. I used this pivot table as a building block for the retention rates table. 

#### First Purchase Sheet
![first purchase sheet](https://github.com/user-attachments/assets/0280168e-b785-4dd9-87d4-22d2e248b405
This table is filtered down by order date with the MIN function to show the first purchase date each user made.

#### Purchase Activity Sheet
![purchase activity sheet](https://github.com/user-attachments/assets/749cb8a9-dd47-4727-80ca-ea18bd133c42)
This sheet shows the purchase activity of each user ID. Part of my project was to add columns G through J. These were used for the cohort analysis table:
1. Column G uses a VLOOKUP to retrieve the first purchase date from the first purchase sheet.
2. Column H is the Event month condenses the event date into YYYY-MM using a TEXT function
3. Column I First purchase month does the same thing but with the first purchase
4. Column J is the cohort age which is found by using a DATEDIF function to find how many months are between each event and purchase date. (This column is utilized in the retention rates sheet)

##### Raw User Data

![raw user data sheet](https://github.com/user-attachments/assets/ea32aae4-a7a8-4dac-9c46-bf542acf9469)
