
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

## My Takeaways:
This problem seemed interesting to solve, and so we ventured to try. As this was our first venture into multiple linear regression, we suffered from trying to make a question fit a model, and not a model fit a question. Along the way I noted that our approach was not without flaws.  Notably, the response variabe of our model is a proportion, so its should be modeled with a sigmoidal curve, not linear. Those advanced statistical models were outside the scope of this class. However, the acutal values for save percentage in the dataset that the model was fit on have low spread (all values between 0.87 and 0.94), and through all our testing we never produced an impossible value (<0, >1). In conclusion our model was reasonably effective (adjusted R-squared value of 0.4), its output is not without it caveats. 

* [Findings presented in accomanied PDF](https://github.com/JordanKeelan/NHL_Goalie_Multiple_Linear_Regression/blob/main/DATA%20603-L02%20Group%201%20Project%20-%20Fall22%20-%20NHL%20Goalies.pdf)
![R Multiple Linear Regression Model Output](https://github.com/JordanKeelan/NHL_Goalie_Multiple_Linear_Regression/blob/main/Model_Output.png?raw=true)

## [Statistical Comparison of Environmental Effects on Alberta Emergency Shelter Occupancy](https://github.com/JordanKeelan/Alberta_Emergency_Shelter_Occupancy_Statistical_Analysis)
* Statistical Analysis using R, two topics investigated:
  1. Has the covid-19 pandemic created a significant increase in emergency shleter occupancy? Has it increased the quantity of people experiencing homelessness?
  2. Did the COVID-19 pandemic result in a greater proportion of women seeking emergency shelter compared to other the 2014 oil downturn?
      * [Reporting on 'Shadow Pandemic' of increased domestic violence during covid lockdowns.](https://www.alberta.ca/article-the-shadow-pandemic.aspx)
* A Simple Linear Regression Model was employed to determine a trend in emergency shelter occupancy rates, to 95% confidence, and compared to actual values recorded.
* Analysis of Difference of Proportion carried out to identify statistically significant increased in womans shelter occupancy in the first 12 months of the Covid-19 lockdown compared to first 12 months of 2014 downturn.
* Dataset cleaning and transformations done in R
* [Findings presented in accomanied PDF](https://github.com/JordanKeelan/Alberta_Emergency_Shelter_Occupancy_Statistical_Analysis/blob/main/Data%20602%20Project.docx.pdf)
