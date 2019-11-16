![](media/rId20.jpeg){width="5.833333333333333in" height="2.1in"}

![](media/rId21.png){width="5.833333333333333in"
height="2.1014173228346458in"}

Removed latitude & longitude extreme outliers & labeled gender as Male,
Female and Unknown.

![](media/rId22.png){width="5.833333333333333in"
height="2.82464457567804in"}

**Tableau Prep Builder 2019.3 \| Output File.**
===============================================

![](media/rId24.png){width="5.833333333333333in"
height="2.576014873140857in"}

Combining the output of 2015, 2016, 2017 & 2018 with my filters took
over 30 minutes to generated providing me with over 53 million records.

Even more excitement brewed than just with the quick preview from the
union stencil output to Tableau Desktop. The 1969 anomaly was even
highlighted even more by creating some quick graphs quickly showed a
spike in 1969 of 'unknown' gender with over 1.3 million records. I will
dismiss this data has probably the unknown defaults in some sort of form
entry defaults. Having the Gender, Birth Year as columns and Sum of all
records below produced this interesting spike in confused 50 year olds.

![](media/rId25.png){width="5.833333333333333in"
height="3.785417760279965in"}

By removing the sorted Gender and just using the birth year and sum of
records, the spike was quite obvious.

![](media/rId26.png){width="5.833333333333333in"
height="3.7733234908136484in"}

1.  **How many trips have been recorded total during the chosen
    period?** 51.5 million trips have been recorded utilizing the data
    from 2015 to the end of 2018.

2.  2015: 8.6 million

3.  2016: 12.2 million

4.  2017: 14.7 million

5.  d.2018: 16 million

![](media/rId27.png){width="4.694444444444445in"
height="7.055555555555555in"}

2.  **By what percentage has total ridership grown?**

![](media/rId28.png){width="5.833333333333333in"
height="3.793079615048119in"}

This rider growth graph shows the growth continuation from Jan 2015 to
Dec 31th 2018. There is a gap in the data for Q4 of 2016 between
September 26

th
==

2016 to Dec 31 \# st 2016.

3.  How has the proportion of short-term customers and annual
    subscribers changed?

![](media/rId30.png){width="5.833333333333333in"
height="3.8039370078740156in"}

**4. What are the peak hours in which bikes are used during summer
months?**

![](media/rId31.png){width="5.833333333333333in"
height="4.174636920384952in"}

**Again no surprise here, very logical that the peak hours during the
summer months of June, July & August are early morning at 8am and peak
between 5 & 6pm.**

**5. What are the peak hours in which bikes are used during winter
months?** ![](media/rId32.png){width="5.833333333333333in"
height="4.497329396325459in"} Again no surprise here, very logical that
the peak hours during the summer months of December, January & February
are early morning at 8am and peak at 5pm.

**6. Today, what are the top 10 stations in the city for starting a journey? (Based on data, why do you hypothesize these are the top locations?)** 
====================================================================================================================================================

![](media/rId34.png){width="5.833333333333333in"
height="1.5622550306211724in"}

So it seems that the top 10 starting stations are relatively close to
New York City Subway line.

![](media/rId35.png){width="5.833333333333333in"
height="7.553120078740157in"}
![](media/rId36.png){width="4.655461504811899in"
height="5.084033245844269in"}

**7. Today, what is the gender breakdown of active participants (Male v.
Female)?**

![](media/rId37.png){width="5.833333333333333in"
height="3.3177832458442693in"}

**8. How does the average trip duration change by age?**
========================================================

![](media/rId39.png){width="5.833333333333333in"
height="3.2746391076115486in"}

**9. Which bikes (by ID) are most likely due for repair or inspection in the timespan?**
========================================================================================

![](media/rId41.png){width="5.833333333333333in"
height="3.3864227909011375in"}

![](media/rId42.png){width="5.833333333333333in"
height="1.8243689851268592in"}

**Well isn\'t that just delightful...**

![](media/rId43.png){width="5.833333333333333in"
height="1.9444444444444444in"}

**Steps taken to still publish effort to Tableau.**

\*\* 1. Source data filtered to only include 2015 data.\*\*

![](media/rId44.png){width="5.708333333333333in"
height="6.277777777777778in"}
