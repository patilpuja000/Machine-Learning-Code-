I have followed the steps from analyzing the given data with its numerical or categorical columns, to Cleaning the data by finding the NaN or bad data present in the given data. I used the fillna with 0 to start with and later realized i could have used mode. Since it did not impact my findings i did not change to mode but i aware that it could have been a better approach.
Next i started hypothesizing the questions by the available pandas methods and plotting the visualizations.
In my visualization i could not leverage the distribution aspect as we did not have numeric data expect for income.
I have used plotly library to plot the graphs and tried to use others as per visibility. Also some comments  seem to be striking out when using compared word. This should be the case it is not strike out.


Below are the findings based on the analysis for the Bar coupon accepted vs not accepted.

Based on the observations i can see that drivers accepted the coupon and visited the bar in between 1~3 or 4~8 times whose age is between 21 -30 and mostly Unemployed and Sales & Related occupation who are either single or married but Alone when compared to the once with the drivers who did not accept the coupon.
I also , realize that if a take data distribution samples for Bar in 1~3 and 4~8 and try to correlate i will get some more insights. I could not analyze that though. But a note to check in deeper.
I see the Accepted coupon drivers are more likely to go in 1~3 around 60% however i also see that drivers not accepted the coupon more than once as well around 40%.






Below are the findings based on the analysis for the Coffee House coupon accepted vs not accepted.

Based on he observations i can see that Drivers in between age 21-30 are visiting the CoffeeHouse in 1~3 times than not accepting. I tried to see if any correlation with gender matter for the analysis, however i could not see an impact for both accepted and not accepted coupons. So i started to look for passenger who are not alone what is ratio they visiting more than 4 Times vs those who did not accept the coupon. I see the number is less to visit for a friend , partner or Kid more than 4times who accepted the coupon. 
Next marital status not single , i see married partner are more likely to visit the CoffeeHouse 1~3 and 4~8 times vs not accepted the coupon.

Overall The CoofeeHouse analysis tells me that within the age 21 -30 drivers who are married are more likely to go to CoffeeHouse 1~3 times vs not accepting the coupon.