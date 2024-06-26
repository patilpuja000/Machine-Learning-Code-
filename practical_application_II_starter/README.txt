Business Understanding :
In real world identifying the right car with a budget is a huge decision, So identifying right factors that can help make a desicion for the car prices high or low is the goal. 
This can be achieved by taking the given dataset, building and evaluating different regerssion models and find the factors/features that will impact the car price to increase or 
decrease.


Model building and evaluation along with the feature findings are presented in the .py file.

Next Steps : 
1. Based on the predicted model , my next steps will be to re analyze the data and see what better ways i can clean the skewed data like converting the NAN with MICE approach 
   instead of mode.
2. To handle the zero values instead of replacing them by just mode.
3. Using other distribution for building instead of sqrt like YeoJohnson.
4. How to handle the value rangin from 1 - say 5000 so we can balance data for the predictions.
5. I know i did approach by deleteing the data with giving a threshold , however that can be eliminated with other cleaning approaches.
6. I also learned that handlingly categorical features with one hot encoding can give better results when compared to ordinal encoder.

n the .py file i attempted to create a table of the interesting findings , however in the Github is all combined and not in a readable format.

Recommendations : 
From the prediction analysis , we can recommend  the customer that the car that has good fueling mechanism , which a better transmission and latest year can cost higher when 
compared to other features like condition, manufacturer, type, size may vary the price from high to low.
