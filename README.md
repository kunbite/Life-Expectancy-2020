# Life-Expectancy-2020
The project aimed to analyze a World Development Indicators (WDI) dataset to predict life expectancy at birth using various statistical and machine learning techniques. The analysis involved extensive data preprocessing, handling missing values, and developing the best linear model to predict life expectancy in 2020.

# Objectives:
To perform exploratory data analysis (EDA) on the WDI dataset.<br/>
To handle missing values using multiple imputation.<br/>
To check for multicollinearity and apply feature selection methods.<br/>
To build and compare linear models for predicting life expectancy.

# Technologies Used:
RStudio<br/>
R (including libraries like dplyr, ggplot2, mice, olsrr)

# Key Achievements
Conducted thorough EDA to understand data distribution and summary statistics.<br/>
Applied multiple imputation to handle missing data, ensuring unbiased estimations.<br/>
Identified and removed highly collinear variables to improve model performance.<br/>
Compared full and reduced linear models using ANOVA, AIC, and Mallow’s Cp.<br/>
Determined that the full model was more effective for predicting life expectancy.

# Key Findings
The response variable, life expectancy at birth, was negatively skewed, indicating longer life expectancies in most countries.<br/>
Variables such as Adjusted.net.national.income, Educational.attainment, Literacy.rate, and Renewable.energy.consumption were removed due to high collinearity and missing values.<br/>
The full model, which included all significant predictor variables, was the best fit for predicting life expectancy.<br/>
 
 # Conclusions
The full linear model was determined to be more accurate and reliable for predicting life expectancy compared to the reduced model.<br/>
Proper handling of missing data and collinearity is crucial for building robust predictive models.<br/>
The findings can be used to inform policy decisions and improve health outcomes by identifying key factors affecting life expectancy.<br/>

# Machine Learning Models
Linear regression was the primary method used for prediction.<br/>
Multiple imputation was employed to handle missing data effectively.<br/>
Variance Inflation Factor (VIF) was used to check and address multicollinearity.

# Implications
The project demonstrates the importance of thorough data preprocessing and proper model selection in predictive analytics.<br/>
Insights from the model can guide interventions aimed at improving life expectancy.<br/>
The methodology can be applied to similar datasets for other predictive modeling tasks.
