![](images/image001.jpg)

Data sets were downloaded from the linked website and easily merged
using a dos command prompt due to the gigantic nature of the data. 2015
through 2018 was chosen because 2019 data was incomplete. 2013 and 2014
may have bad data and having not completely refined their process yet
may not have a full data set. For sake of size and time and interest in
comparing data over years, a very large data set of over 53 million
records are analyzed below.\
\
![](images/image002.png) 

To complement the learning done in class, I completed the **Linkedin
Learning: Cleaning, Transforming and Prepping Your Data With Tableau
Prep** course online in order to be skilled with using Tableau Prep
Builder 2019.3 to clean such a huge dataset. I also followed along to
**Linkedin Learning: Creating Interactive Tableau Dashboards**\
\
\
\
\
**Key Filtering Steps:**\
\
Kept trip duration \<25000 seconds.\
Birth year \> 1930 and removed null values\
\
cleaned 2017 column names that needed to be renamed to align with 2015,
2016 & 2018 data so that the resulting fields would have no mismatching
fields.

![](images/image003.png)

Removed latitude & longitude extreme outliers & labeled gender as Male,
Female and Unknown.

![](images/image004.png)

**Tableau Prep Builder 2019.3 \| Output File.** 
=================================================================================================================
![](images/image005.png)
Combining the output of 2015, 2016, 2017 & 2018 with my filters took
over 30 minutes to generated providing me with over 53 million records.

Even more excitement brewed than just with the quick preview from the
union stencil output to Tableau Desktop. The 1969 anomaly was even
highlighted even more by creating some quick graphs quickly showed a
spike in 1969 of 'unknown' gender with over 1.3 million records. I will
dismiss this data has probably the unknown defaults in some sort of form
entry defaults. Having the Gender, Birth Year as columns and Sum of all
records below produced this interesting spike in confused 50 year olds.

![](images/image006.png) 

By removing the sorted Gender and just using the birth year and sum of
records, the spike was quite obvious.\
\
![](images/image007.png) 

By removing the unknown gender as a filter we achieve a very nice
graph.\
\
![](images/image008.png) 
\
\
\
**Data Utilized: 2015, 2016, 2017, 2018:**\
\
Questions to Answer:

**1. How many trips have been recorded total during the chosen period?**
    =================================================
	
    51.5 million trips have been recorded utilizing the data from 2015
    to the end of 2018. ( 1.5 is unknown gender )

    a.  2015: 8.6 million

    b.  2016: 12.2 million

    c.  2017: 14.7 million

    d.  2018: 16 million\
        \
        \
		
		
\		
![](media/image009.png) 
\

  **2. By what percentage has total ridership grown?**
    =================================================
\
![](images/image010.png) 
\
 This rider growth graph shows the growth continuation from Jan 2015 to
 Dec 31th 2018. There is a gap in the data for Q4 of 2016 between
 September 26^th^ 2016 to Dec 31^st^ 2016.

  **How has the proportion of short-term customers and annual subscribers changed?**
=================================================
\
![](images/image011.png)
\
It's logical to see how the drop off of subscribers in Q1 of every year
it being the winter months in New York.

**4. What are the peak hours in which bikes are used during summer months?**
=================================================
\
![](images/image012.png)

**Again no surprise here, very logical that the peak hours during the
summer months of June, July & August are early morning at 8am and peak
between 5 & 6pm.**

**5. What are the peak hours in which bikes are used during winter months?**
=================================================
![](images/image013.png) 
Again no surprise here, very logical that the peak hours during the
summer months of December, January & February are early morning at 8am
and peak at 5pm.

**\
**

**6. Today, what are the top 10 stations in the city for starting a journey? **
====================================================================================================================================================
(Based on data, why do you hypothesize these are the top locations?)** 
![](images/image014.png) 

So it seems that the top 10 starting stations are relatively close to
New York City Subway line.**\
\
![](images/image015.png) 
![](images/image016.png) 
**

**\
**

**7. Today, what is the gender breakdown of active participants (Male v. Female)?**
=======================================================================================
\
![](images/image017.png) 
\
Here is a chart that shows gender by birth year with the **Sum** of the
duration of the trips. While a vastly different graph below shows the
**AVG trip** duration is much more weighted towards older subscribers
enjoying the old style of transportation, perhaps during their bike
through central park during the day. I believe strongly that the 1935 /
2018 data for both male and females need to be weeded out. There a
smaller spike for males born in 1931 for the 2015 data set.\
\

![](images/image018.png) 

**8. How does the average trip duration change by age?**
========================================================

![](images/image019.png)
\

It would be worth diving deeper to analyze the spike in people born in
1935. After parsing out the graph, it's easy to see how there's an
anomaly in the 2018 data which is the root cause of the odd number
spike.\


![](images/image020.png) 

**9. Which bikes (by ID) are most likely due for repair or inspection in the timespan?**
========================================================================================

![](images/image021.png) 
\
While playing with the charts an interesting point revealed itself. The
above chart is showing the total records by Bike ID and it's logical
that the lower number bike ids ( in the 16k to 18k ranges ) are the
older bikes that have been on the services the longest since 2015 which
begged me to ask the question how could I show that which brought to me
to this graph by adding the year as a colour dimension.\
\
![](images/image022.png) 
\
There seems to be a real explosion of new bikes brought into service in
2016 and then a whole new wave in 2018.


** PROBLEMS **
========================================================================================
![](images/image023.png) 

**Well isn't that just delightful...\
\
![](images/image024.png) 

**Steps taken to still publish effort to Tableau.**
========================

1. Source data filtered to only include 2015 data.

![](images/image025.png) 
\
![](images/image026.png)
\
![](images/image027.png) 
![](images/image028.png)


