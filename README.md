# A/A/B Testing in an Online Grocery Store

I work at a startup that sells grocery products. We need to understand how users behave in our mobile application. In this project, we will analyze the sales funnel. We will find out how users move toward making a purchase. How many users complete a purchase, and how many “drop off” at earlier stages? At which specific steps does this happen?

After that, we will analyze the results of an A/A/B experiment. The designers wanted to change the fonts in our application, but the managers were concerned that users might find the new fonts unfamiliar. It was decided to rely on the results of an A/A/B test. Users were divided into three groups: two control groups with the old fonts and one experimental group with the new fonts. We will determine which font performs better.

Creating two A groups instead of one has certain advantages. If the two control groups show similar results, we can be confident in the accuracy of the experiment. If there are significant differences between them, it may help identify factors that caused distortions in the results. Comparing the control groups also helps us understand how much time and data will be required for future tests.

## Technical Project Description
Conducted an end-to-end product analytics project analyzing user behavior in a mobile grocery application and evaluating the impact of a UI font change using an A/A/B experiment.

- Cleaned and prepared event log data (243k+ events, 7.5k+ users) using Pandas.
- Converted timestamps, engineered features, removed duplicates, and filtered incomplete periods.
- Performed exploratory data analysis to assess traffic stability and group balance.
- Built a conversion funnel:
  - Main Screen → Offers → Cart → Payment
  - Identified ~38–40% drop-off at the first transition step.
  - Calculated overall conversion (~48%).
- Implemented a custom two-proportion Z-test in Python.
- Conducted 16 hypothesis tests (A/A and A/B comparisons).
- Interpreted p-values at α = 0.05.

## Key Technical Skills Applied
- Python (Pandas, NumPy, SciPy)
- Data cleaning & feature engineering
- Funnel & conversion analysis
- A/B testing & hypothesis testing
- Statistical interpretation
- Data visualization (Matplotlib, Seaborn, Plotly)
