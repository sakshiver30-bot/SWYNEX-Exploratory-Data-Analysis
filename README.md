# SWYNEX Task 2: Exploratory Data Analysis

## Dataset
Cleaned Titanic dataset from Task 1 (891 rows, 11 columns).

## Tools Used
Python (pandas, matplotlib, seaborn) in Google Colab

## Analysis Performed
- Summary statistics (mean, median, min, max)
- Survival rates by sex, class, age group, port and family size
- Distribution and outlier analysis of Age and Fare
- Correlation heatmap

## Key Insights
1. **Sex was the strongest factor:** 74.2% of women survived compared to 18.9% of men. The overall survival rate was 38.4%.
2. **Passenger class mattered:** survival fell from 63.0% in 1st class to 47.3% in 2nd class and 24.2% in 3rd class.
3. **Fare reflects class:** the median fare was 60.29 in 1st class, 14.25 in 2nd class and 8.05 in 3rd class.
4. **Children had the best chances:** the Child group (0-12) had a 57.4% survival rate, compared to 35.3% for Young Adults and 22.7% for Seniors.
5. **Port of embarkation showed a difference:** Cherbourg (C) 55.4%, Queenstown (Q) 39.0%, Southampton (S) 33.9%. This is likely linked to class.
6. **Family size had a sweet spot:** families of 2-4 survived at 55.3% to 72.4%, versus 30.4% for people travelling alone. Very large families did much worse.
7. **Anomaly:** the Age chart has a spike at 28 because missing ages were filled with the median in Task 1.

## Charts
1. `1_survival_by_sex.png`
2. `2_survival_by_class.png`
3. `3_age_distribution.png`
4. `4_fare_by_class.png`
5. `5_survival_by_age_group.png`
6. `6_survival_by_family_size.png`
7. `7_correlation_heatmap.png`

## Files
- `cleaned_data.csv`: dataset from Task 1
- `SWYNEX_Exploratory_Data_Analysis.ipynb`: full code and outputs
- `*.png`: charts
