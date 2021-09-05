# **__Green Stocks Analysis__**
## **Project overview**

The green stocks analysis project studies the stock market over the past couple of years in order figure out which stocks have been going up more consistantly in order to help our client, Steve, and his parents to invest in the best option. 

## **Results**
### __Stock Performance__

![This is an image](https://github.com/Loulwa-Alkaisi/VBA_Challenge/blob/6ab29d9a4040c33f85883c55763d0228b61cf0c3/assets/VBA_Challenge_2017_Analysis.png)

Based on the results that we found in the picture above, in the year of 2017 most of the tickers in stock market came back with a positive return except for the ticker TERP which came back with a return of -7.2%. If we look at all the other tickers we can see that the best in that year were DQ, ENPH, FSLR, and SEDG. 

![This is an image](https://github.com/Loulwa-Alkaisi/VBA_Challenge/blob/6ab29d9a4040c33f85883c55763d0228b61cf0c3/assets/VBA_Challenge_2018_Analysis.png)

On the other hand when we look at the 2018 analysis of the stock market we can see a huge difference compared to 2017. In 2018 most of the tickers came back with a negative return besides two which were ENPH and RUN. 
Based on these result we can say that the best option to invest in is ENPH. The reason is that RUN had a low return in 2017 of 5.5%, while ENPH had a relatively high return in both years. In 2017 it had a return of 129.5% and in 2018 the return was 81.9%. 

### __Execution Time__

Before we refactored our code the execution time for the 2017 analysis was **0.8125** seconds and for the 2018 analysis it was **0.8203125** seconds. 

![This is an image](https://github.com/Loulwa-Alkaisi/VBA_Challenge/blob/6ab29d9a4040c33f85883c55763d0228b61cf0c3/assets/VBA_Challenge_2017.png)

![This is an image](https://github.com/Loulwa-Alkaisi/VBA_Challenge/blob/6ab29d9a4040c33f85883c55763d0228b61cf0c3/assets/VBA_Challenge_2018.png)

After we refactored our code we noticed that the code took more time to run than in the original code. For the 2017 analysis it took **0.8828125** seconds to run and for the 2018 analysis it took **0.8945312** seconds to run. 

![This is an image](https://github.com/Loulwa-Alkaisi/VBA_Challenge/blob/6ab29d9a4040c33f85883c55763d0228b61cf0c3/assets/VBA_Challenge_refactored_2017.png)

![This is an image](https://github.com/Loulwa-Alkaisi/VBA_Challenge/blob/6ab29d9a4040c33f85883c55763d0228b61cf0c3/assets/VBA_Challenge_refactored_2018.png)

## **Summary**
### __Advantages of refactoring:__

There are many advantages to refactoring a code but I think some of the main advantages are it helps in improving the design and structure of the code and it is an efficiant way to maintain that code. Moreover, it make that code easier to read and it reduces the potential bugs. 

### __Disadvantages of refactoring:__ 

Like anything else everything has some advantages and disadvantages and some of those disadvantages for refactoring are that if we have a very large code it could be risky to refactor and it could possibly increase the amount of bugs instead of decreasing them. Additionally refactorying may be time consuming for the developer. 

### __How do these pros and cons apply to the VBA script?__

In the case of our VBA code the disadvantages did not apply as much because our code was not very big and it was not time consuming. On the other hand, refactoring definitly helped with improving the design and the structure and it made it easier to read for me personally. 