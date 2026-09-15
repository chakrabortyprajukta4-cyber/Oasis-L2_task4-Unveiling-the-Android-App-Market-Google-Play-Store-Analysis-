# Oasis-L2_task4-Unveiling-the-Android-App-Market-Google-Play-Store-Analysis-
This project demonstartes mainly about the Android App Market. # Unveiling the Android App Market – Google Play Store Analysis

## Objective

The objective of this project is to analyze the Google Play Store dataset to understand app categories, ratings, installations, pricing, app size, estimated revenue, and user review sentiment. The analysis helps identify trends and useful insights about the Android app market.

## Steps Performed

1. Loaded the Google Play Store apps and user reviews datasets using Pandas.
2. Removed duplicate records and rows with missing app names.
3. Cleaned the **Installs, Price, Rating, Reviews, and Size** columns.
4. Removed records with missing crucial values such as Rating and Installs.
5. Analyzed the most common app categories.
6. Visualized the distribution of app ratings.
7. Examined the relationship between app size and number of installs.
8. Compared free and paid applications.
9. Analyzed the distribution of prices for paid applications.
10. Calculated estimated revenue using **Price × Installs**.
11. Identified the top revenue-generating categories.
12. Performed sentiment analysis on user reviews using **VADER**.
13. Classified reviews as Positive, Negative, or Neutral.
14. Merged review sentiment with app categories for category-level analysis.
15. Created an interactive Plotly visualization of ratings and installs.
16. Saved the cleaned app and sentiment datasets as CSV files.

## Tools & Technologies

* **Python**
* **Pandas** – Data cleaning and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Plotly** – Interactive visualization
* **VADER Sentiment** – User review sentiment analysis
* **Jupyter Notebook / VS Code** – Development environment

## Dataset

The project uses two main datasets:

* `googleplaystore.csv` – Google Play Store application data
* `googleplaystore_user_reviews.csv` – User review data

## Visualizations

The analysis includes:

* Top 15 app categories
* App rating distribution
* App size vs. installs
* Free vs. paid app distribution
* Paid app price distribution
* Interactive rating vs. installs by category

## Outcome

The project successfully cleaned and analyzed Google Play Store data and generated insights into app popularity, ratings, pricing, estimated revenue, and customer sentiment. The analysis also provides useful recommendations such as focusing on high-rated categories, considering freemium pricing strategies, and monitoring user feedback after app launches.

## Output Files

* `cleaned_googleplaystore.csv` – Cleaned and processed app dataset
* `reviews_with_sentiment.csv` – User reviews with sentiment scores and classifications

## Conclusion

This project demonstrates how **Exploratory Data Analysis, data visualization, revenue estimation, and sentiment analysis** can be combined to understand the Android app market and support data-driven app development and marketing decisions.

