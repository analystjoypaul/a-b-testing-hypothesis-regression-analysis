# A/B Testing for Marketing Campaigns

This project focuses on analyzing marketing campaign performance using **A/B testing and statistical hypothesis testing** to determine whether a new campaign variant leads to a statistically significant improvement in conversions.  
It is intended for **data analysts, marketing teams, and decision-makers** who rely on data-driven experimentation.

## Business Problem
Marketing teams often run multiple campaigns, but not all lead to meaningful improvements.  
This project answers:

- Does the new marketing campaign increase conversion rate?
- Is the observed uplift statistically significant or due to random chance?
- Should the business roll out the treatment campaign at scale?


## Experiment Design
- **Control Group**: Users exposed to the existing campaign
- **Treatment Group**: Users exposed to the new campaign
- **Primary Metric**: Conversion Rate
- **Statistical Significance Level (α)**: 0.05


## Tools & Technologies
- **Python**
- **Pandas & NumPy** – Data cleaning and manipulation  
- **Matplotlib & Seaborn** – Data visualization  
- **SciPy / Statsmodels** – Hypothesis testing  
- **Jupyter Notebook** – Analysis workflow


## Analysis Workflow
1. **Data Loading & Cleaning**
   - Handled missing values
   - Ensured data consistency across experiment groups

2. **Exploratory Data Analysis (EDA)**
   - Distribution of users across control and treatment
   - Conversion rate comparison
   - Visualization of key metrics

3. **Hypothesis Testing**
   - Null Hypothesis (H₀): No difference in conversion rates
   - Alternative Hypothesis (H₁): Treatment campaign improves conversion
   - Performed statistical tests to evaluate significance

4. **Result Interpretation**
   - Compared p-value against significance level
   - Quantified uplift and practical impact


## Key Insights
- The treatment group showed a **higher conversion rate** compared to the control group
- Statistical testing confirmed whether the difference was **significant**
- Results provide actionable guidance for campaign rollout decisions



## Authors

- **Joy Paul**  
  Data Analyst · Python · SQL · Statistics · A/B Testing  


## Demo

 Jupyter Notebook–based analysis  
- End-to-end A/B testing workflow  
- Data preprocessing, hypothesis testing, and result interpretation  


## Links

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/)
[![portfolio](https://img.shields.io/badge/portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](#)


## Skills

- **Programming:** Python (Pandas, NumPy, SciPy)  
- **Statistics:** A/B Testing, Hypothesis Testing, Confidence Intervals  
- **Analytics:** EDA, Conversion Analysis, KPI Measurement  
- **Tools:** Jupyter Notebook, Excel, Power BI  
- **Domain:** Marketing Analytics  


## Used By

- Marketing & Growth teams  
- Product & Experimentation teams  

## Acknowledgements

- A/B Testing & Statistical Inference methodologies  
- Python open-source analytics ecosystem  

## Badges

![Python](https://img.shields.io/badge/Python-3.9-blue)
![A/B Testing](https://img.shields.io/badge/Statistics-A%2FB%20Testing-green)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)





## FAQ

#### What test is used?
Z-test or T-test depending on sample size and assumptions.

#### Can this framework be reused?
Yes, it can be applied to any A/B testing scenario.


## Feedback

For feedback or collaboration, feel free to connect via **LinkedIn**.

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/ab-testing-marketing-campaigns.git
cd ab-testing-marketing-campaigns

