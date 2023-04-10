# Credit Scoring Card with R

Given the data for about 1000 retail clients credit status and relevant fundamental information, design a scoring card for customers. For decision tree model, 700 samles are selected as training set and the reamining 300 are the test test. The optimal model provide 88.6% correctly categorization, which capture almost all the non-default case. However, in the end the model with 73.4% ROC is selcted after balancing the categorization ability for both default and non-default consumer. 

Sometimes, less is more. Decision tree model to me is quite like the MBTI personality categorization, which makes the process of making decision eaiser, but with less accuracy. Due to time and coding skill restriction, our model can be fixed further with model combinations. Such as futher identify each categories by logistic regression. Even human insticts matters will selecting parameters, Ridge and Lasso regression can be further applied in order to be more objective.


## Library
- dplyr
- glmmTMB
- ROSE(for ROC curve)
- C50(for decition tree)

## Key process
- Data cleaning
- Divided into training and testing group (Use box plot to check if the randomized process got mad and made two groups varies a lot)
- Run GLMM and Decision Tree Model
- Graphing for better undersanding
- Interprete the parameters
- Use ROC to evaluate the model


Organized info shown in the my partial [slides](https://github.com/HaoyueTan/Credit-Scoring-Card-Construction-with-R/blob/main/FIN6120%20Slides_H.pptx)
