# NCAA Women's Basketball Team Ranking Analysis: Sports Analytics & Statistical Modeling Project

## Project Overview
Developed a comprehensive statistical analysis to evaluate NCAA women's basketball team rankings using advanced machine learning techniques. This project investigated whether traditional ranking systems accurately reflect team performance by incorporating overlooked factors like home-court advantage and temporal dynamics through sophisticated Bradley-Terry modeling.

## Statistical Modeling: 
- Implemented four distinct Bradley-Terry logistic regression models for comparative analysis
- Applied penalized regression techniques to prevent overfitting and improve model generalization
- Incorporated temporal analysis to track team strength evolution throughout the 2024-2025 season
- Used maximum likelihood estimation for parameter optimization

## Model Selection
- Performed systematic model comparison using Akaike Information Criterion (AIC) for optimal model selection
- Implemented Bayesian-penalized Bradley-Terry models with home advantage parameters
- Conducted cross-validation and model performance evaluation across multiple frameworks
- Applied regularization techniques to handle high-dimensional sports data

## Hypothesis Testing
- Executed rigorous hypothesis testing with Bonferroni correction for multiple comparisons
- Calculated confidence intervals and standard errors using variance-covariance matrices
- Performed pairwise team comparison analysis with statistical significance testing
- Controlled familywise error rates in multiple testing scenarios (α = 0.05/3)

## Probability Modeling:**
- Computed win probability predictions for tournament matchups with quantified uncertainty
- Developed team strength rankings based on statistical coefficients rather than simple win-loss records
- Analyzed home-court advantage effects across 300+ Division I women's basketball teams
- Created predictive models for tournament outcome forecasting

## Data Processing 
- Processed comprehensive NCAA Division I women's basketball dataset (2024-2025 season)
- Handled temporal data conversion and date-class object manipulation
- Managed binary outcome variables and categorical team identifiers
- Implemented data cleaning and preprocessing for large-scale sports datasets

### Key Analytical Findings
Model Performance: 
- Identified optimal model (Bradley-Terry with home-court advantage) achieving AIC score of 5052.4
- Demonstrated that home-court advantage significantly improves prediction accuracy compared to baseline models
- Quantified model performance differences across four distinct analytical approaches

Predictive Analytics Results:
- Generated probabilistic forecasts: Michigan vs. Georgia (86.3% win probability), Ohio State (81.3%), Michigan State (72.1%)
- Ranked top 10 teams (UCLA, South Carolina, Texas, USC, UConn, etc.) based on statistical strength coefficients
- Identified bottom-performing teams with statistical confidence measures

Statistical Significance:
- Achieved statistically significant results for Michigan vs. Georgia matchup (p < 0.000017 after Bonferroni correction)
- Demonstrated rigorous hypothesis testing methodology with appropriate multiple testing corrections

## Complexity Factors
- Analyzed 300+ teams across full collegiate basketball season
- Implemented 4 distinct statistical models with comparative analysis
- Performed hypothesis testing across multiple team matchups with appropriate corrections
- Generated probabilistic predictions with quantified confidence intervals

