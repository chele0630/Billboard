# Billboard
#[![INSERT YOUR GRAPHIC HERE](https://upload.wikimedia.org/wikipedia/commons/2/2b/Billboard_Hot_100_logo.jpg)]()


<!-- TABLE OF CONTENTS -->
## Table of Contents

* [Team Billboard](#team-billboard)
* [Purpose of the Analysis](#purpose-of-the-analysis)
* [Methodology](#methodology)
* [Findings](#findings)
* [Limitations](#limitations)
* [Coding Style](#coding-style)
* [Authors](#authors)


# Team Billboard

Team Billboard chose to gather information on Billboard charts from June 1999 to December 2000.  We plan to use information on genres, songs and artists to find trends that will tell us about trends.   Our goal is to determine if the position that a song enters the Top 100 chart correlates to the position in which that song peaks.  Specifically, we are looking to answer the question: Are songs that enter the Billboard Top 100 in the top quartile more likely to peak at the number one position?  

We will be using Billboard data from https://www.billboard.com to give us information on the songs that have been on the Billbord charts from June including how  We used information from www.wikipedia.com to find which songs were number one during this time frame and how long they stay in the number one position.   We will be using Tableau to perform analytics and displaying multiple visuzaulizations.

## Purpose of the Analysis

Our primary purpose is to gather data using our sources determine if there is a correlation between the starting point of a song on the Billboard Top 100 Charts and that song peaking at number one while on the chart.   After evaluating this information, we will be able to determine the story being told through the data and answer our inital question.


## Methodology

We merged data from  https://www.billboard.com and https://www.wikipedia.com using the melting method and cleaned it using Python programming language. We exported the file to csv and imported it into Tableau.  


## Findings



## Limitations
Our data is from a limited time frame.  If we were able to used data from a broader time frame, we would be likely to get more accurate comparison to determine correlation.  Songs released in 1999 will end up having longer time on the data charts in comparison to those released in December 2000.  

## Next Steps

A future feature would be to evaluate the data in relation to a single artist vs solo artist to determine which is most popular and trends for the top 10.
We can also use album sales to determine how much revenue each single has produced.  
We can also break down the data according to gender to determine if which is most popular and trends for the top 10.


## Coding Style

Python programming language was used, the list of dependencies are as follows:

```sh
import datetime
import pandas as pd

```


## Authors

Gael, Escoffrey, Van, Lori, Jessica, Velindia, Kavya, SMurphy
