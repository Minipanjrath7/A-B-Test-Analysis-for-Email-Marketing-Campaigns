# A/B Test Analysis for Email Marketing Campaigns

## Overview
This project evaluates the effectiveness of personalized emails (B-variant) compared to standard boilerplate emails (A-variant) through A/B testing. Using statistical techniques, measured the lift in conversion rates and analyzed campaign performance across various customer segments.

## Objective
To determine whether personalized emails lead to higher conversion rates and provide actionable insights for optimizing future email marketing campaigns.

## Tools and Technologies
- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Scipy, Seaborn, Matplotlib

## Dataset
The dataset contains records of a fictional subscription-based company, including:
- **user_id**: Unique identifier for each user
- **date_served**: Date the email was served
- **marketing_channel**: Primarily focus on Email
- **variant**: A/B test group (A-variant: control, B-variant: personalized)
- **converted**: Whether the user converted (True/False)
- **language_displayed** : Language in which the campaign is displayed
- **language_preferred**: User's preferred language
- **age_group**: Age group of the user
- **date_subscribed**: Date on which the user subscribed
- **date_canceled** : Date on which user cancelled the subscription
- **is_retained**: Whether user retained or not


## Methodology
1. **Data Evaluation**: Evaluated whether the data is enough for A/B analysis.
2. **Descriptive Analysis**: Examined conversion rates across segments.
3. **Statistical Testing**: Conducted hypothesis testing (t-tests) to measure the significance of results.
4. **Lift Calculation**: Calculated the percentage increase or decrease in conversion rates between variants.
5. **Visualization**: Used bar charts to represent segment-wise performance.

## Key Findings & Recommendations already mentioned in the Notebook!


---

## Repository Structure
- **data/**: Contains the dataset used for analysis
- **notebooks/**: Includes Jupyter notebooks for data cleaning, analysis, and visualization
- **README.md**: Project overview and documentation

---

Feel free to explore and contribute!

