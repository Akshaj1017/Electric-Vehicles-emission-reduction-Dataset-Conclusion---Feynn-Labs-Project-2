# Electric Vehicles emission reduction Dataset Conclusion Feynn Labs Project 2

## Conclusion 1:
![image](data:image/png;base64,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)

"annual_ghg_emissions_reductions_mt_co2e" refers to the amount of annual greenhouse gas (GHG) emissions that have been reduced or avoided, measured in metric tons of carbon dioxide equivalent (MT CO2e). This metric is commonly used to track progress in reducing GHG emissions, which contribute to climate change. The term "CO2e" refers to the amount of CO2 that would have the same warming effect as the combination of all other GHGs, such as methane and nitrous oxide.

We see that the count of annual_ghg_emissions_reductions_mt_co2e with the value between 2 and 3 is more in the datset which means that the count of total amount of greenhouse gases emissions (measured in metric tons of CO2 equivalent) that have been reduced in a given year is between 2 and 3 is large which is good for the environment.

This reduction can be due to various measures taken to mitigate emissions such as the adoption of renewable energy sources, energy efficiency improvements, or carbon capture and storage technologies.

Since our dataset is concerned with electric vehicles, this means that if the businesses develop electric cars in India it would be beneficial to the environment sin
