# Play Store Apps Data Cleaning & Preprocessing

## 📌 Introduction
The Google Play Store hosts a vast array of applications, and analyzing the associated data offers immense value for businesses, developers, and researchers. By cleaning and preprocessing this dataset, we can derive meaningful insights that enhance app development, market analysis, and user engagement strategies.

In this project, we will tackle data cleaning tasks such as handling missing values, fixing inconsistent entries, detecting outliers, and ensuring the dataset is ready for analysis. Additionally, we will explore key analytical questions to extract valuable insights.

---

## 📂 Dataset Overview
The dataset contains various features related to Play Store applications. Below is a summary of the key columns:

| Column Name        | Description |
|-------------------|-------------|
| **Application Name** | Name of the application |
| **Category** | Category the app belongs to |
| **Rating** | Overall user rating of the app |
| **Reviews** | Number of user reviews |
| **Size** | Size of the app |
| **Installs** | Number of user downloads |
| **Type** | Whether the app is Free or Paid |
| **Price** | Price of the app |
| **Content Rating** | Targeted age group (e.g., Everyone, Mature 17+) |
| **Genres** | Additional genres the app belongs to |

---

## 🛠 Data Cleaning & Preprocessing Tasks
To ensure the dataset is well-structured and ready for analysis, the following tasks will be performed:
- **Fix Rating**: Handle missing and inconsistent rating values.
- **Fix Size**: Convert size values into a consistent numerical format.
- **Fix Price**: Ensure price values are correctly formatted and numeric.
- **Fix Category**: Standardize category labels and correct inconsistencies.
- **Fix Android Version**: Handle missing or incorrectly formatted Android version values.
- **Handle Missing Values**: Address missing data using appropriate imputation techniques.
- **Outlier Detection and Handling**: Identify and manage outliers in numerical columns.
- **General Cleaning**: Fix any other inconsistencies that may arise.

---

## 📊 Analytical Questions & Insights
Once the data is cleaned, we will answer the following analytical questions:

1. **What is the most expensive app on the Play Store?**
2. **Which genre has the highest number of apps?**
3. **What is the average size of free vs. paid apps?**
4. **What are the top 5 most expensive apps with a perfect rating (5)?**
5. **How many apps have received more than 50K reviews?**
6. **What is the average price of apps, grouped by genre and number of installs?**
7. **How many apps have a rating higher than 4.7, and what is their average price?**
8. **What is Google's estimated revenue from apps with 5,000,000+ installs?** *(Assuming Google takes a 30% cut from app sales.)*
9. **What are the maximum and minimum sizes of free vs. paid apps?**
10. **Is there a correlation between an app’s rating, number of reviews, size, and its price?**
11. **How many apps exist for each type (free/paid) across different content ratings?**
12. **How many apps are compatible with Android version 4.x?**
