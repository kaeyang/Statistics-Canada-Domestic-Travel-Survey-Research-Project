# Statistics-Canada-Domestic-Travel-Survey-Research-Project

<h2> Description </h2>
The goal of this analysis conducted using R programming is to present the 2004 Canadian Travel Survey dataset and the 2 research questions:

1. What are the trends of domestic trips recorded throughout the year?
2. What proportion of domestic trips use automobiles as opposed to other modes of transportation?

This project also explains how answering these 2 questions would be applicable in solving global issues. 

The dataset was mainly collected by Statistics Canada, and I applied additional cleaning and wrangling to create 2 additional datasets to answer the research questions. After the 2 datasets were created, a linear regression model was used to answer the 1st research question, while Maximum Likelihood Estimation and Bayesian Inference were used to answer the 2nd question. Confidence intervals and credible intervals were constructed to give a range of values that the parameter of interest could fall in. Lastly, I conducted a hypothesis test to determine if the proportion of automobile users have decreased in 2004 compared to 1994. 

For the 1st question, a general increasing trend of 520 trips was observed between January and August. For the 2nd question, it was found that 85.8% of domestic trips use automobiles as their main source of transportation. The results of the hypothesis test concluded that 2004 proportion was indeed less than that of 1994. Even though this analysis answered the research questions, the age of the dataset along with the infrastructure, technological, social, and economic change between 2004 and today in 2021 may limit the applicability of the results. To supplement the results of this analysis, one can consider comparing the trends of domestic trips with international trips. One can also research into the reasons why automobiles are more favorable compared to other transportation modes.

<br>

<h2> R Packages </h2>
ggplot2, knitr, qwraps2, reshape2, skimr, tidyverse, viridis, visdat, 
