# 7.🧪🧪 A/B Experiment

## 🚀 Project Description
As an analyst at a large online store, you worked with the marketing department to compile a list of hypotheses that could help increase revenue.

Your task was to:
1. Prioritize hypotheses based on their potential impact.
2. Launch an A/B test to evaluate the effectiveness of proposed changes.
3. Analyze the results to determine actionable insights for business improvement.
This project focuses on data preprocessing, hypothesis testing, and decision-making based on the results of an A/B test.

## 📊 Data Description
Data for Hypothesis Prioritization
File: /datasets/hypotheses_us.csv
* Hypotheses: Brief descriptions of hypotheses.
* Reach: User reach, on a scale from 1 to 10.
* Impact: User impact, on a scale from 1 to 10.
* Confidence: Confidence in the hypothesis, on a scale from 1 to 10.
* Effort: Resources required to test the hypothesis, on a scale from 1 to 10 (higher values indicate more effort).

Data for A/B Test Analysis
/datasets/orders_us.csv
* transactionId: Order identifier.
* visitorId: User identifier for the order.
* date: Order date.
* revenue: Order revenue.
* group: A/B test group (A or B).
  
/datasets/visits_us.csv
* date: Date.
* group: A/B test group (A or B).
* visits: Number of visits on the specified date and group.

Note:
Before analysis, the data was carefully preprocessed to identify and handle potential issues such as visitors appearing in both test groups or incorrect data entries.

## 🎯 Key Analysis Goals
Prioritize hypotheses using ICE and RICE frameworks.
Compare conversion rates, revenue, and other key metrics between test groups.
Verify the statistical significance of results using hypothesis testing.
Provide data-driven recommendations to improve marketing strategies and revenue growth.

## 🛠️ Technologies Used
* Programming Languages: Python
* Data Analysis: Pandas, NumPy, SciPy
* Hypothesis Testing: Stats
* Data Visualization: Matplotlib, Seaborn

## 📈 Skills Developed
* Data Cleaning and Preparation.
* Calculation of relevant metrics such as conversion rates and revenue.
* Hypothesis prioritization with ICE and RICE frameworks.
* Visualization and reporting of A/B test results.
* Decision-making based on statistical evidence.

🔗 Project Link:  https://github.com/Jeduardocastel/7.-A-B-Experiment/blob/main/project_10.ipynb
