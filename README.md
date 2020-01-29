# ASHRAE---Great-Energy-Predictor-III

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRtUgBIuYDxHSefxEXFsP7VPpkiPpmswM4oRTQ1GSZbhdIxTk9ttw&s)

Q: How much does it cost to cool a skyscraper in the summer?

A: A lot! And not just in dollars, but in environmental impact.

Thankfully, significant investments are being made to improve building efficiencies to reduce costs and emissions. The question is, are the improvements working? Under pay-for-performance financing, the building owner makes payments based on the difference between their real energy consumption and what they would have used without any retrofits. The latter values have to come from a model.

Through this project, I developed models using LightGBM and CatBoost to predict metered building energy usage. The rationale behind chosing LightGBM was that it handles categorical data without much preprocessing while being fast at the same time and behind CatBoost was that it handles categorical data without any processing and performs well without much tuning. The data comes from over 1,000 buildings over a three-year timeframe. With better estimates of these energy-saving investments, large scale investors and financial institutions will be more inclined to invest in this area to enable progress in building efficiencies. 
