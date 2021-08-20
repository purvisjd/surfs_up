# Surf's Up with Ice Cream!

##  Overview of Analysis:
The ultimate goal of this analysis is to determine if whether patterns can negatively impact the potential for opening up combination surf and ice cream shops in Hawaii.  Weather data for approximately a 7 year timespan was obtained in the form of an SQLite database and was then processed utilizing Python and VS Code to determine whether patterns and see if it would be advisable to open such a shop given known weather patterns.  For this particular analysis, the focus was placed on temperature in the months of June and December to see if the business model would be (weather permitting) sustainable year round.

###  Resources:
*    Data:[Hawaii Weather Data](https://github.com/purvisjd/surfs_up/blob/main/hawaii.sqlite)
*    Software Used:  Anaconda, Jupyter Notebook 6.3.0, SQLite, Python, VS Code

##  Results of Analysis
A significant amount of data was available for both requested months to cover approximately a 7 year timespan.  This provides a strong indication of general weather patterns to take into consideration when determining the viability of the business venture.

###  Key differences
*  First key difference between the data sets is the total number of data points available.  June produced 1700 data points whereas December only shows 1517.  The likely cause for this difference is that there is not an equal number of recordings; June has recordings going up through 2017 whereas December does not have any recordings represented during that time frame.  
*  There is a significant difference between the minimum temperatures recorded for the two months with June showing 64 and December showing 56.  This information should be taken into account as there is a far reduced demand for ice cream or water based activities when the temperature reaches that low of a level.  The ice cream sales would almost certainly be reduced during that timeframe.
*  The third difference of note is actually information that should be seen as rather encouraging.  Between the two months, there is only a relatively small difference with temperature readings for the various percentiles, typically only a difference of only 2-3 degrees.  This actually bodes well for the potential for continuing the business during the "winter" months.

##  Summary
The general information obtained during this analysis can be constrewed as very encouraging.  The temperatures remain relatively consistent throughout the year with the only real differences being the extreme values (i.e., highest recorded and lowest recorded) which indicates an increased potential for success for running the business year round, with at least some potential for reduced sales during the winter months.  Some additional weather data that would be beneficial for this particular analysis would be to query the precipitation(i.e., rainfall)for the area as 1), particularly since it was a lack of knowledge of rain patterns that negatively impacted our investor's first forray into a similar business venture.  In addition to the precipitation information, it would also be helpful to query out the location of the specific stations drawing the information so as to be able to identify the best locations to establish the stores based on the associated weather patterns.  Some stores may do better in June than in December while others may be the reverse. 
