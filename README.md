# Branding Activity Analysis
This project was done to analyse the impact of an increased level of branding activity conducted in Australia and to assess if it produced a noticeable increase in the number of transactions. This assessment was done by comparing the results of an exposed area to increased digital advertisements (Western Australia) against the results from an non-exposed area (South Australia) where there was no change in advertising.

## Input
* branding_experiment_data.csv: Time-stamped data containing relevant statistics from across Australia (all states) over the period from 2019-01 to 2021-06. 

![image](https://user-images.githubusercontent.com/62014067/127532383-c85494ba-4e55-4eea-b23b-92b7d362eee4.png)

## Analysis
* branding_analysis.ipynb: This Jupyter notebook provides detailed analysis and documentation of the process.

## Key Observations
Regarding the specific increase in transactions:
* At the end of the first year (2019), we observe an overall 17.3x increase in transactions for WA (exposed area) vs a 16.5x increase in SA (non-exposed area).
* At the end of the second year (2020), we observe an overall 42.8x increase in transactions for WA vs a 42.0x increase in SA.
* In our last month (2021-07), we observe an overall 53.2x increase in transactions for WA vs a 51.9x increase in SA.

If we consider other metrics, we also notice that at the end of our last month (2021-07):
* There was an overall 56.1x increase in new users in WA vs 51.2x in SA.
* There was an overall 48.1x increase in users in WA vs 45.5x in SA.
* Negligible difference in overall increase in sessions and transactions revenue for WA vs SA (<0.5x).

## Results
From these results, we can conclude that there was an observable small increase in the number of transactions in the exposed area (WA) relative to the non-exposed area (SA). However, there was also a noticeably larger increase in number of users and new users over this period for WA relative to SA.

Thus, we can conclude that the digital video campaign was successful in delivering an increase in the number of transactions, albeit not as significant as might be expected. However, this also accompanied a significant increase in the number of users and new users, which should be factored into consideration as well. An increase in userbase might also be another important factor for assessing impact of branding activity in the future.
