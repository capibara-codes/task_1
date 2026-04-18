# task_1 Summary
Task one: Exploratory Data Analysis on School Performing data. School Performance Analysis: Project Summary The Objective I analyzed 5,200 school records to identify which factors—infrastructure, teacher experience, or location—actually drive academic success.

Technical Workflow Data Cleaning: Managed ~1,000 missing values using Median & Mode Imputation. I also "clipped" erroneous percentage data (e.g., negative literacy rates) to ensure a realistic 0–100% range.

Feature Engineering: Created a custom Avg_Score metric (combining Math, Science, and Language) to provide a holistic view of school performance.

Modeling: Developed a Linear Regression model to test the impact of physical resources on grades.

Insights Geography is Not Destiny: Urban and Rural schools performed almost identically (~61.4%). In this dataset, location does not dictate success.

The Infrastructure Paradox: While 90% of schools have power, only 30% have internet. Surprisingly, internet access and teacher experience showed very weak correlations with test scores.

The Library Factor: Schools with libraries showed a consistent, though small, performance lead, suggesting that access to physical learning materials remains vital.
