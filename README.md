# zameen.com
 
Real Estate data from Zameen.com for the cities of Karachi, Islamabad and Lahore were taken from kaggle.

The data was analyzed and cleaned in colab. 
  1) Useless columns were removed.
  2) Type and area columns were corrected.
  3) Outliers were removed.
  4) Data was normalized by 2*SD.
  5) Zero/ null / impossible values were removed.

The cleaned data was used to make a dashboard on Power BI.

A machine learning model was also trained on this cleaned data using grid search method which had an accuracy of 91%.

### This is the Power BI dashboard which can be used to get more insights.

![Predictions](/../main/pictures/power_bi_dashboard.png)

#### Some problems with the dataset
1) Almost all of the selling and renting have been done in the month of November.
2) Karachi has no rent data while lahore and islamabad have no sale data.

                   The dataset is pretty unbalanced
