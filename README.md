# Christopher Back Coding Challenge Submission

For my project I tested this hypothesis: Car price and customer satisfaction will be directly correlated, with consumer ratings rising as prices rise up to a certain point. After this certain point, the ratings plateau or fall.

1.) Import needed libraries, and import dataset into a pandas dataframe

2.) Since we're just working with price and consumer rating, drop all other columns in the dataframe

3.) Clean up the Price column into just numerical data. Transform all $ currency values as a float by removing $ and comma signs

4.) Categorize rows into price ranges ($10k, $20k,... $90k)

5.) Import modules needed for visualization

6.) Visualize distribution of each price range (this is incldued in PriceDist.png)

7.) Now lets use a scatterplot to see if there is any correlation between price and customer satisfaction (this is included in priceVSrating.png)

Conclusion:

Looks like our hypothesis was wrong. There is no apparent correlation shown in the scatterplot.

***Did not finish- not sure why $90k range is out of order on the x axis.

Findings:

<img width="1051" alt="PriceDist" src="https://user-images.githubusercontent.com/70988841/215040511-b5f48089-4fdf-4b94-a9f5-54e5d47a864f.png">
<img width="1067" alt="priceVSrating" src="https://user-images.githubusercontent.com/70988841/215040528-74f109b9-33cf-43e9-bed0-c8c3ad231607.png">
