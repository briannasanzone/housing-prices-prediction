## Project 2 - Ames Housing Data and Kaggle Challenge


### Problem Statement
Compass Real Estate is a real estate firm that promotes innovationthrough the use of technology to streamline the selling and buying process. Upon research of the technology used, Compass Real Estate utilizes and transforms quarterly market reports to provide invaluable insights for their agents to make the buying and selling experience more "intelligent and easier." Additionally, Compass provides a service, Compass Concierge, that provides tools and assistance for home improvement when selling a home including staging, flooring, painting, etc. However, I was unable to find any information on any technology/intelligence Compass utilizes to streamline this service. This project takes the position as a consultant for Compass Real Estate that aims to create a model that can be used by agents or home owners/sellers who utilize Compass Concierge to understand the most important features that drive sale price when buying or selling a home and what changes should be made to get the best price available. This is important because there are so many factors to consider when buying or selling a home. This can turn into a rather lengthy and ultimately stressful process for everyone involved. Reducing this time and stress with the proper tools is of utmost importance to turn what was once considered a miserable experience into somwthing much simpler and enjoyable. 
[Compass](https://www.compass.com/about/)



### Executive Summary

In order to execute this problem, I decided to create a model with the goal of predictability while still being able to maintain interpretability. This would empower the agent or home owner with the knowledge of which features can be improved to increase the price. The project used the Ames, Iowa housing prices dataset to predict sale price based off of various features of a home.
The dataset consisted of 81 features of a home with 2051 records. The model consisted of 29 features 
All records were preserved to decrease variance of the model to better predict unseen data. The model found to be the best consisted of 29 features, not including 15 feature interactions that explored qualitative features vs quantitative features. The accuracy of the model on the training data was 86.3% and aprroximately 90% accurate on testing data that was used to represent 'unseen' data. The features of the model was then split into qualitative features and quantitative features to evaluate if one was more important than the other. Due to time restrictions, there were no feature interactions included in the model. The model based off of qualitative features only had an accuracy score of 77% when predicting sale price and the model based off of quantitative features had an accuracy score of 76% when predicting sale price. However further research and model evaluation should be done in order to accurately assess the relationship between qualitative features and quantitative features when predicting sale prices.

---

### Data Dictionary

[Data Dictionary](https://www.kaggle.com/c/dsi-ames/data) 

---


### Conclusion & Recommendations
Overall, the model achieved its goal of preserving interpretability while maintaining an accuracy of approximately 90% when predicting sale price. Not surprisingly, the model created tells us that features such as overall condition and overall quality of the home are important drivers of sale price. Additionally, features such as 1st floor square feet, 2nd floor square feet, kitchen quality, number of bathrooms, basement and garage quality, condition, and square feet are associated with changes in sale price of a home. This knowledge will allow realtors to focus on these features when improving the home and getting it ready for selling. For example, above ground living area and kitchen quality had a strong relationship when predicting sale price. This can be used by the realtor or home owner by specifically improving
these features directly or improvement of these features indirectly by conveying a more social area living space as these are what these two features tell us upon further inspection. However in the absence of one or more of these features, can the sale price of the home be maintained when improving another feature such as the quality or condition. Further research and modeling should be done in order to assess this. This is important because not everyone's home fits into a black box and the service and model should always aim to serve down to the individual level. Every data point or relationship found is a person and it is important to be inclusive to better serve that person. As we can see from the model, data alone does not drive business, relationships do. 

