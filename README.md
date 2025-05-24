# Airbnb Investment Analysis Project

This project determines the best area in Manhattan to invest in Airbnb properties. It includes analysis across 10 different Excel sheets, each serving a specific purpose.

## [Airbnb Investment Analysis Excel Project](https://docs.google.com/spreadsheets/d/1qc_atGeVcNktWB89Ainw1OgWWvR4uierhLiiSuasY38/edit?usp=drive_link)

### Project Overview
The project contains 10 Excel sheets:
1. **Start Here Page** - Table of contents and summary of project results.
2. **Assumptions and Change Log** - Details assumptions and tracks changes throughout the process.
3. **Raw Listings Data** - The raw dataset before cleanup.
4. **Cleaned Listings Data** - The cleaned-up version of the raw data.
5. **Calendar Data Analysis** - Works with calendar dates in the dataset.
6. **Top 10 Most Popular Neighborhoods** - A pivot table showing the most popular neighborhoods.
7. **Average Price + Occupancy** - Calculates annual revenue for each neighborhood.
8. **Most Popular Rentals by Bedroom Count** - Highlights neighborhood popularity by rental size.
9. **Average Occupancy by Listing ID** - Averages occupancy rates per listing.
10. **Data Dictionary** - Glossary of terms used in the project.

---

## Key Takeaways
This project demonstrates data cleaning, analysis, and visualization to support investment decisions. It highlights Excel's capability in handling real-world datasets and driving actionable insights.

### Sheet Descriptions and Screenshots

#### **1. Start Here Page**
Table of contents for the project and summary of results.

![Start Here Page](https://github.com/user-attachments/assets/12343b82-4d3e-4a54-b813-99406cd7ce88)

---

#### **2. Assumptions and Change Log**
Details assumptions made for the project and tracks changes throughout.

![Change Log Sheet](https://github.com/user-attachments/assets/0fbc58c6-596a-439d-ad58-72ef3510d18f)

---

#### **3. Raw Listings Data**
The raw data before cleaning.

![Raw Listings Data](https://github.com/user-attachments/assets/a499cb16-24d9-45a6-a64d-2e1433294595)

---

#### **4. Cleaned Listings Data**
The cleaned version of the raw data. Key changes include:
1. Removing duplicates.
2. Normalizing data fields.

![Cleaned Data](https://github.com/user-attachments/assets/424854fa-e464-49a5-ad7c-a479e7843a8d)

---

#### **5. Calendar Data Analysis**
Analyzes calendar dates with an `IF` function to categorize occupancy as `0` or `1`.

![Calendar Page](https://github.com/user-attachments/assets/5b356f3e-6a07-49e8-92b8-92e1a6477b34)

---

The purpose of this sheet was to find the number of bedrooms per Airbnb, if they were available, the price of each place, when the data was loaded.

---

#### **6. Top 10 Most Popular Neighborhoods**
Pivot table showing the most popular neighborhoods based on review counts.

![Top 10 Neighborhoods](https://github.com/user-attachments/assets/760e27ad-1992-493f-8982-46292057260a)

Through this pivot table, I found that the most popular neighborhoods were:

1. Lower East Side - 6242
2. Hells Kitchen -	5506
3. Harlem -	5157
4. Midtown -	4128
5. Upper West Side -	3497
6. Chelsea -	2913
7. East Village -	2572
8. East Harlem -	2175
9. West Village -	1735
10. Upper East Side -	1696	

---

#### **7. The Average Price + Occupancy for Neighborhoods in Descending Order **
Calculates annual revenue by dividing the average occupancy rate by the average price for each neighborhood.

![AVG Occupancy and Price](https://github.com/user-attachments/assets/8c2ab63a-996d-438d-a9d3-daaa2ca26dea)

Because we're looking at the Lower East Side:

1. The average occupancy rate is 81.65%
2. The average price for an Airbnb property is $331.53
3. The annual revenue for properties in the Lower East Side is $98,807

---

#### **8. Most Popular Rentals by Bedroom Count**
Shows the popularity of rentals by bedroom count (0–5 beds) for each neighborhood.

![Popular By Bedrooms](https://github.com/user-attachments/assets/f9181bd6-f9fa-4fbd-8554-245aa6a3dcb2)

The Lower East Side ranks #1 in this table based on bedroom count:

1. The total reviews in the Lower East Side for properties that have 0 bedrooms comes to 340
2. The total reviews in the Lower East Side for properties that have 1 bedroom come to 5028
3. Combined, this totals 5730 properties

---

#### **9. Average Occupancy by Listing ID**
Pivot table summarizing the sum and average occupancy for each listing ID.

![AVG Occupancy by ID](https://github.com/user-attachments/assets/68f64e85-8f89-40f1-9231-083e5e92a4da)

---

#### **10. Data Dictionary**
Glossary of terms used in the project.

![Data Dictionary](https://github.com/user-attachments/assets/27f1edf3-40ae-46ad-a33e-99a274e1acf0)
