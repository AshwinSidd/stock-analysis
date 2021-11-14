# stock-analysis

## **Overview of the project**

In this project, the purpose was to refactor our VBA code to ensure that it runs faster and accurately for the data across two years - 2017 and 2018. The idea was to get well versed with refactoring and also think about how to make the code work for more data across more timelines. Looping through various data, especialy nested loops was the key to this project and ultimately refactoring it in a way that it works even when data is increased. Finally, the goal for this module was to come up with a refactored data that worked effeciently and quickly.

## **Results**

**Performance of stocks** - The data for both the years, 2017 and 2018 were analyzed. In comparison between the 2 years, the stocks performed very well in the year 2017 with most stocks yielding higher returns compared to the year 2018. In 2017, as shown in the image below, except for 1 stock (TERP), all other stocks yielded a postiive growth/returns.

![VBA_Challenge_2017](https://user-images.githubusercontent.com/92342751/141688904-95af5ac2-9e74-4ea1-9e80-341896f3b253.PNG)

While in the year 2018, most stocks did not perform well. As shown in the image below, barring a couple of stocks (Run and ENPH), none of the other stocks returned a good yield. This probably could be attributed to the almost depression-like situation that occured in 2018. As per my research using google and reading across many articles, it was noticed that the year 2018 was not a good one for stocks. America's trade war with China, the slowdown in global economic growth and concern that the Federal Reserve was raising interest rates too quickly all contributed to a pessimistic reaction from the stock market. 

(Source: https://www.pbs.org/newshour/economy/making-sense/6-factors-that-fueled-the-stock-market-dive-in-2018)

![VBA_Challenge_2018](https://user-images.githubusercontent.com/92342751/141688911-1e3f302f-e21a-44cb-bb38-37a1f7073ea8.PNG)

**Run times** - Now with the code refactored, the execution times for both the analysis for the respective years too reduced significantly. Below image is of the refactored code for reference.

![image](https://user-images.githubusercontent.com/92342751/141688987-e7a99f60-47fc-400a-bf2c-2c72a069d950.png)

For 2017, the refactored code ran in just 0.1484375 seconds while the original script took a good minute. In 2018, the code ran in a good 0.15234 seconds.

## **Summary**

**Advantages and disadvantages of refactoring code** - Refactoring a code ensures that the data can run smoothly and quickly. Cleaning the code and organizing them well enough may sound tedious and disadvantageous, given the effort required. But it has to be noted that cleaning and organizing the codes will only make them run quicker and smoother while also making the code more standardised than repetitive. Most times in the real world, the codes are lengthy enough, where the run times are for hours together, hence refactoring code will esnure the best and most minimal time it would require for thr same code to run. Hence it is imperative and advantatgeous to refactor codes.  

**Pros and cons of refactoring VBA code for our stock analysis** - The data for our stock analysis was not exhaustive. Having said that, cleaning and organizing the VBA code in the assignment turned out to be a blessing as it gives a detailed picture of every action that was being taken. Right from initiailizing the ticker index to formatting the code in the end, the code is detailed and each action listed as to ensure that if anyone else has to rework the code, they have all the information to work on it. More importantly, cleaning the code also decreased the run times substantially which is a huge plus. 




