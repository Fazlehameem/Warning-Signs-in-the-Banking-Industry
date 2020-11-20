# Warning Signs in the Banking Industry
![bank](https://media.brstatic.com/2017/03/20164944/what-happens-when-bank-fails-1-intro-lg.jpg)

In this project, we utilize Python visualizations to create an interactive dashboard examining the differences in loan concentrations between active banks that made it through the 2008-2010 global financial crisis and those that failed that in that timeframe or in the years thereafter.  Our main focus is on how the banks that managed to make it through the financial crisis positioned their loan portfolios compared to those that didn't make it through - what were the differences in concentrations?  For banks that failed, were they too heavily concentrated in one particular area?  Did excessive risk lead to failure?  We want currently active banks to be able to look at this analysis and glean relevant information they can then use to better allocate their loan portfolio.

Team members include Ben Fischler, Mitchel Voloshin, Lisa Esberger, Brendan Shanley and Fazle Hameem.

## Question 1: How do the credit concentrations at midsize banking firms affect the long-term success of the entity?
![Plot1.1](/Pics_of_Plots/Plot1.1.png?raw=true  "Plot 1")
![Plot1.2](/Pics_of_Plots/Plot1.2.png?raw=true  "Plot 1 Continued")

![Plot2](/Pics_of_Plots/Plot2.png?raw=true  "Plot 2")

One of the clear conclusions we reached was that banks that did not make it through the 2008-2010 global financial crisis were too heavily concentrated in risky loan categories, such as Non-Owner occupied.  What we expected to see was that active banks that made it through that crisis would have lower concentrations - and that is exactly what we found.  The first set of plots show RE concentrations in general, and we see the same thing - banks that failed during/post crisis had RE concentrations that were 1000+% of their Tier 1 Capital + Allowance, while active banks that survived the crisis did so with much smaller concentrations in RE loans in general.  Banks that survived the crisis seem to have more *diverse* portfolios than those that did not survive.


## Question 2: What role did the concentrations play in the failure of banking firms over the last 20 years?
![Plot3](/Pics_of_Plots/Plot3.png?raw=true  "Plot 3")

![Plot4](/Pics_of_Plots/Plot4.png?raw=true  "Plot 4")

It is tough to draw a causal relationship between Loan Concentration Portfolios and the success of banks, as there are many other factors in play.  What our plots did was show us one part of the equation, and help us see a clear picture regarding the differences between how active banks handle their loan portfolios, and how failed banks did so.  One of the more interesting set of plots we developed was the set of 3 scatter plots showing 1-4 Family Residential Real Estate exposure for each group of banks.  One of the things we see is that for banks that failed either in 2008-2010 or in the years that followed, many of the banks' residential portfolio sizes actually *increased*, while banks that made it through the crisis, their residential portfolio sizes tended to remain stagnant or decline.  These renderings helped us see that banks that made it through the crisis may have anticipated the housing market collapse and pulled back on its residential loans, while those banks that failed did not see it coming and did not lower their concentrations in residential RE.


## Question 3: What trends, if any, were discovered that eventually led to bank insolvency?
![Plot5](/Pics_of_Plots/Plot5.png?raw=true  "Plot 5")

![Plot6](/Pics_of_Plots/Plot6.png?raw=true  "Plot 6")

Various trends were discovered with regards to how each set of banks split up their loan portfolios, as discussed in this ReadMe.  Yet once again, we cannot say that this portfolio diversification was a causal factor of the banks' success or failure - all we can say is that it *appears* to be a factor in a banks' overall health.  

For the above visualizations, we used heatmaps to show both the individual loan concentrations as well as the banks' concentrations in Consruction & Development.  One of the more interesting findings in the Construction & Development heatmap was that Rock Canyon bank, one of the active banks that made it through the crisis, had very high concentrations in Construction & Development (similar to failed banks) while other active banks had much smaller concentrations in Construction & Development.  This told us that Construction & Development may not be as important a loan category as others, as while other categories were pretty consistent in terms of their loan concetrations per set of banks, we saw in that Construction & Development, different banks may have different philosphies on the category and therefore may place different weights on it, but that will not have as strong an impact on the success of the overall portfolio than say, weights in the Non-Owner Occupied category.


## Question 4: How can this data be used by investors or by firm management to make future operational decisions?
![Plot7](/Pics_of_Plots/Plot7.png?raw=true "Plot 7")

We believe the conclusions reached in this project can truly benefit firm management to make operational decisions in the future.  Our main conclusion is simple: *diversify* your loan portfolios across varying segments, while keeping your exposure in particularly risky categories, like Non-Owner Occupied, low.  The numerical and visual conclusions tell a clear story: Real Estate loans in general are risky, and especially in today's climate of Covid-19 in which certain segments of Real Estate are struggling, it is more important than ever to understand the importance of loan diversification and learn from the mistakes of those banks that failed during the 2008-2010 global financial crisis.

## Limitations:
Rather than banks increasing their individual concentrations in certain loan categories and that being the reason for increasing percentages of Tier 1 Capital + Allowance, another option was that the banks Tier 1 Capital + Allowance decreased, thereby increasing the individual loan concentrations percentages.  Therefore, our analysis of loan concentrations  should be considered a starting point for determining the causes of bank failures - a stronger study would be to incorporate each individual banks' Tier 1 Capital + Allowance into the data in order to see more clearly how those fluctuations, in addition to actual higher concentrations, impact the percentages.  