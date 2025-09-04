# Play Store Data Analysis

## Overview
This project analyzes two datasets from the Google Play Store: `Play Store Data.csv` (app details) and `User Reviews.csv` (user sentiments). The analysis, performed in Python using a Jupyter Notebook (`Play_Store_analysis.ipynb`), explores app performance, user behavior, and trends.

## Problem Statement
The analysis addresses 20 questions, including:
1. Factors influencing app ratings.
2. User review sentiment patterns by category/content rating.
3. Content ratings with higher/lower user ratings.
4. Average reviews per category.
5. Seasonal trends in installs/ratings.
6. Free vs. paid app rating differences.
7. Most competitive app categories.
8. Categories with consistently high ratings.
9. Top Play Store categories.
10. Average app rating.
11-12. Top free/paid apps.
13. Android versions by category.
14. Sentiment percentage.
15. Apps with most negative reviews.
16. Subjectivity histogram.
17. Paid app content ratings.
18. Effect of last update on ratings.
19-20. Distribution of app updates (yearly/monthly, free/paid).

## Analysis Done
1. **Libraries**: NumPy, Pandas, Matplotlib, Seaborn.
2. **Data Loading**:
   - `Play Store Data.csv`: 10,841 rows, 13 columns (e.g., App, Category, Rating, Reviews).
   - `User Reviews.csv`: Not fully loaded in notebook but assumed for sentiment analysis.
3. **Data Cleaning**:
   - Nulls: Dropped 2 rows (Type, Content Rating); 1474 nulls in Rating, 8 in Current Ver, 3 in Android Ver.
   - Outlier: Rating=19 (likely error).
4. **EDA**:
   - Stats: Mean rating ~4.19, range 1-19.
   - Visualized free app updates by month (July peak).
   - Grouped data for free/paid apps, update trends.
5. **Partial Analyses**:
   - Explored ratings, updates, and categories.
   - Sentiment analysis (from `User Reviews.csv`) implied but not implemented in visible code.

## Final Outcome
- **Key Insights**:
  - Average rating: ~4.19.
  - Free apps: Most updates in July; dominate in volume.
  - Categories: 'FAMILY' frequent; competitiveness not fully analyzed.
  - Sentiment/Content: Patterns partially explored; needs review data.
  - Updates: No strong rating correlation; mid-year update spikes.
- 
-
