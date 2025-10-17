### Notes from building a machine learning model for predicting FX rates

---

<br>
<br>
Initially, the plan was to predict daily exchange rates to allow stakeholders like traders and financial market players make close to real time predictions for exchange rate values. GDP data for both Ghana and the US was collected and up-sampled to daily values. The same technique was used for any other feature that needed to be up-sampled to daily values such as interest rates data which is recorded monthly for the US.
Now this has some effects for prediction purposes. Machine learning models will eventually tend to make predictions based on smooth data or some assumptions.

For example, the GDP for the first quarter of 2024 will carry through for all the days of the month within that quarter making the model think that value was constant when in reality, the growth of an economy barely stays the same
