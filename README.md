# MachineLearningInBusiness
## Sprint 9 -  Machine Learning in Business
**Project Summary:** Utilized Linear Regression models to forecast oil reserve volumes in new locations, aiming to maximize profit margins by informing strategic business decisions.  **Technical Skills:** Linear regression, predictive modeling, business analytics, and data interpretation.

## Project Description


I work for the OilyGiant mining company and my task is to find the best place for a new well.

These will be the steps to choose the location:

Collect the oil well parameters in the selected region: oil quality and volume of reserves;
Build a model for predicting the volume of reserves in the new wells;
Pick the oil wells with the highest estimated values;
Pick the region with the highest total profit for the selected oil wells.
I have data on oil samples from three regions. Parameters of each oil well in the region are already known. I will build a model that will help to pick the region with the highest profit margin. I will analyze potential profit and risks using the Bootstrapping technique.
DATA Description:

I have been given exploration data for three regions stored in three files.
id — unique oil well identifier
f0, f1, f2 — three features of points (their specific meaning is unimportant, but the features themselves are significant)
product — volume of reserves in the oil well (thousand barrels).

CONDITIONS:
- Only linear regression is suitable for model training (the rest are not sufficiently predictable).
- When exploring the region, a study of 500 points is carried with picking the best 200 points for the profit calculation.
- The budget for development of 200 oil wells is 100 USD million.
- One barrel of raw materials brings 4.5 USD of revenue The revenue from one unit of product is 4,500 dollars (volume of reserves is in thousand barrels).
- After the risk evaluation, keep only the regions with the risk of losses lower than 2.5%. From the ones that fit the criteria, the region with the highest average profit should be selected.

The data is synthetic: contract details and well characteristics are not disclosed.

## Conclusion

After all the calculations and analysis performed, I would suggest to OilyGiant that Region TWO should be selected for the oil well.

- It had the lowest predicted average volume of oil reserves, but with the lowest RMSE.
- It was calculated to have the second highest total volume of oil reserves.
- After bootstrapping, it was the region with the highest mean profit and lowest risk of negative profit.
