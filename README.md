# WFH-Employee-Burnout-Productivity-Analysis
This project investigates the critical intersection of remote work behavior and employee well-being. Using a dataset of 1,800 records, I performed an end-to-end data analysis to identify the behavioral drivers of burnout and quantify its direct impact on organizational productivity.

Technical ImplementationBuilt entirely with Python, the project leverages Pandas and NumPy for robust data cleaning and feature engineering—specifically the creation of a "Productivity Index" to normalize output against work duration. I utilized Matplotlib and Seaborn to conduct Exploratory Data Analysis (EDA), employing correlation matrices, distribution plots, and regression analysis to visualize the "Performance Tax" of exhaustion.

Key Findings:
The Productivity Crisis: Discovered a massive -0.96 correlation between burnout and task completion rates, proving that burnout is a primary inhibitor of business ROI.Digital Intensity vs. Duration: Screen time emerged as a stronger predictor of burnout (r = 0.12) than total work hours or sleep deprivation, highlighting "Digital Fatigue" as a core issue.
Threshold Identification: Analysis revealed a "9-Hour Danger Zone," where burnout risk spikes exponentially regardless of breaks taken.
The Sleep Paradox: Correlation with sleep hours was virtually zero (-0.006), suggesting that high-intensity burnout cannot be "slept away" if the work structure remains unchanged.

Strategic Impact:
The findings translate into actionable business intelligence:
Meeting Caps: Implementing a 4-5 daily meeting limit to reduce cognitive load.
Digital Detox: Mandatory screen-free intervals to mitigate high-intensity fatigue.
Efficiency Metrics: Shifting performance evaluations from "hours logged" to "output-per-hour" using the Productivity Index.
