
## [Modeling NHL Goalie Save Percentages Based on Player Attributes](https://github.com/JordanKeelan/NHL_Goalie_Multiple_Linear_Regression)

## Problem Statement
NHL teams are big business, and they spend a lot of time and money on player selection. Each team can only dress two goaltenders, so selecting perfromative players is essential. Our goal was to take an approach to goaltender evaluation and performance prediction using data specific to individual goaltenders in a specific season and excluding various team- and game-based factors that could not only vary from year to year, but team to team, and game to game for a specific goaltender.

## Approach
Our approach to solving this problem involved the use of Multiple Linear Regression Model, written in R, that predicts an individual goalie's save percentage based on their attributes. We used data visualization (ggplot) and statistical analysis to identify cutoff values for 'games played' to improve consistency. We manually conducted backward elimination model selection, resulting in a valid interactive model that outperformed automated step-wise selection in terms of RMSE and R squared adj. 

## Model Development
We used Multiple Linear Regression Model to predict an individual goaltender's save percentage. The model was developed in R programming language, and we used ggplot for data visualization. To improve the consistency of our predictions, we identified the cutoff values for 'games played' through statistical analysis. The model was then manually optimized through backward elimination model selection, which resulted in a more accurate model compared to the automated step-wise selection process.

## Model Diagnostics
To ensure the validity of our model, we conducted several model diagnostics, including Linearity, Independence, Equal Variance, Normality of Residuals, Multicolinearity, and Outlier assumptions. We made sure that all the assumptions were satisfied to ensure the robustness and accuracy of our predictions.

## Conclusion
Our project demonstrated the feasibility of using Multiple Linear Regression Model to predict the save percentage of NHL goaltenders based on their individual attributes. Our approach showed an improvement in the accuracy of predictions compared to the traditional methods. The model was optimized through backward elimination model selection, and the model diagnostics confirmed that all the assumptions were satisfied, ensuring the robustness of our predictions.

## What I Learned

In this project, I explored the use of Multiple Linear Regression to evaluate and predict the performance of NHL goaltenders. I encountered some challenges along the way, such as realizing that the response variable of our model, save percentage, was better modeled with a sigmoidal curve rather than a linear model. However, since advanced statistical models were beyond the scope of the class, we continued to work with multiple linear regression.

Despite its limitations, our model was reasonably effective, with an adjusted R-squared value of 0.4, and produced results that were within the acceptable range of values for the response variable. 

Through this project, I gained a deeper understanding of the importance of proper model selection for specific problems, the process of feature selection and model development, and the significance of model diagnostics through assumption testing. I also learned about the limitations and strengths of multiple linear regression models and how they can be used in real-world applications.

* [Findings presented in accomanied PDF](https://github.com/JordanKeelan/NHL_Goalie_Multiple_Linear_Regression/blob/main/DATA%20603-L02%20Group%201%20Project%20-%20Fall22%20-%20NHL%20Goalies.pdf)
![R Multiple Linear Regression Model Output](https://github.com/JordanKeelan/NHL_Goalie_Multiple_Linear_Regression/blob/main/Model_Output.png?raw=true)



# [Statistical Comparison of Environmental Effects on Alberta Emergency Shelter Occupancy](https://github.com/JordanKeelan/Alberta_Emergency_Shelter_Occupancy_Statistical_Analysis)

## Problem Statement
The purpose of this project is to investigate the impact of two societal events - the COVID-19 pandemic and the 2014 oil downturn - on emergency shelter occupancy in Alberta. The project aims to determine if the COVID-19 pandemic created a significant change in emergency shelter occupancy and if it has resulted in a greater proportion of women seeking emergency shelter compared to the 2014 oil downturn.

## Approach
The project investigated two topics:

1. Has the COVID-19 pandemic created a significant difference in emergency shelter occupancy? Has it increased or decreased the quantity of people experiencing homelessness?

  We employed a linear regression Model to determine a trend in emergency shelter occupancy rates and compared the results to actual values recorded. The analysis was performed using R programming language and the dataset was cleaned and transformed in R. 

2. Did the COVID-19 pandemic result in a greater proportion of women seeking emergency shelter compared to other the 2014 oil downturn?

  An Analysis of Difference of Proportion was carried out to identify a statistically significant increase in women's shelter occupancy in the first 12 months of the COVID-19 lockdown compared to the first 12 months of the 2014 downturn.

## Findings
Our linear regression model outlined the decline in emergency shelter occupancy from 2014 to 2020.  Though, as this is time-series data, no real conclusions could be drawn as to the long term effect of covid-19 on shelter occupancy. 



Our proportion comparison of the two downturns did show that womans shelter occupancy was a larger proportion of total shelter occupancy during the first year of the covid-19 pandemic than during the first year of the 2014 downturn. 



## Takeaways
This project provides valuable information on the impact of societal events on emergency shelter occupancy in Alberta. The results of the Simple Linear Regression Model and the Analysis of Difference of Proportion help to understand the trend in emergency shelter occupancy rates and the proportion of women seeking emergency shelter during the COVID-19 pandemic and the 2014 oil downturn. The findings of the project can be useful for policymakers, government agencies, and organizations working to address the issue of homelessness.

This project served again as a great learning tool or me.  As my first foray into linear regression and proportion analysis, I learned a great deal about the limitations of strength of each moethod. Again here, our analysis suffers from the fact that we were given a set of tools and looked for a problem to solve with them, rather than identifying a problem and selecting the best method to solve it. In this case, knowledge of time-series analysis would have made out analysis more meaningful.  

Regaurdless, it was interesting to see that the proportion of emergency occupants in womans shelters did increase in the covid-19 pandemic, but that following the pandemic that proportion hit all time lows. This is especially interesting when you consider that while emergency shelter occupancy rates were dropping steadily in 6 years prior to the pandemic.


* [Findings presented in accomanied PDF](https://github.com/JordanKeelan/Alberta_Emergency_Shelter_Occupancy_Statistical_Analysis/blob/main/Data%20602%20Project.docx.pdf)
