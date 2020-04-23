# Analysis of COVID-19 Data for New York State

*Author: Mark Bauer*  
*Date Created: April 4, 2020*  
*Date Updated: April 23, 2020*

Data Provided by: New York State Department of Health.  
New York State Statewide COVID-19 Testing Data Repository:  
https://health.data.ny.gov/Health/New-York-State-Statewide-COVID-19-Testing/xdss-u53e.     


Data Description: *This dataset includes information on the number of tests of individuals for COVID-19 infection performed in New York State beginning March 1, 2020, when the first case of COVID-19 was identified in the state. The primary goal of publishing this dataset is to provide users timely information about local disease spread and reporting of positive cases. The data will be updated daily, reflecting tests completed by 12:00 am (midnight) the day of the update (i.e., all tests completed by the end of the day on the day before the update).*


# Tables

**Table 1. Cumulative Number of Positives in New York State (Top 10 Counties)**

|    | County      | Cumulative Number of Positives   | Cumulative Number of Tests Performed   |
|---:|:------------|---------------------------------:|---------------------------------------:|
|  0 | Queens      | 44,904                           | 92,530                                 |
|  1 | Kings       | 39,354                           | 85,313                                 |
|  2 | Nassau      | 32,124                           | 76,551                                 |
|  3 | Bronx       | 31,659                           | 68,388                                 |
|  4 | Suffolk     | 29,567                           | 73,696                                 |
|  5 | Westchester | 25,959                           | 78,881                                 |
|  6 | New York    | 19,348                           | 51,268                                 |
|  7 | Richmond    | 10,590                           | 27,320                                 |
|  8 | Rockland    | 9,828                            | 23,734                                 |
|  9 | Orange      | 6,816                            | 19,904                                 |

# Figures


## Bar Charts

![numer of cases by county  barh](figures/cases-by-county-barh.png)  

![epi curve](figures/epi_curve.png)  

##  Number of Positives Per Day
### Top 10 Counties with Number of Positives Cases

### Weekly Average

![days since 10 daily cases top 10 weekly](figures/10-cases-timeseries-by-county-top-10-weekly.png)

![days since 10 daily cases top 10 weekly log](figures/10-cases-timeseries-by-county-top-10-weekly-log.png) 

### Daily

![days since 10 daily cases top 10 daily](figures/10-cases-timeseries-by-county-top-10-daily.png)

![days since 10 daily cases top 10 daily log](figures/10-cases-timeseries-by-county-top-10-daily-log.png)

##  Growth Factor of Number of Positives Per Day
### Top 10 Counties with Number of Positives Cases

![growth factor daily cases top 10 weekly](figures/growth-factor-by-county-top-10-weekly.png)

![growth factor daily cases top 10 daily](figures/growth-factor-by-county-top-10.png)

##  Cumulative Number of Positives
### Top 10 Counties with Number of Positives Cases
![days since 10 cases top 10](figures/10-cases-timeseries-by-county-top-10.png)

![days since 10 cases top 10 log](figures/10-cases-timeseries-by-county-top-10-log.png)

### All Counties in New York State
![days since 10 cases](figures/10-cases-timeseries-by-county.png)

![days since 10 cases log](figures/10-cases-timeseries-by-county-log.png)  


## Trajectory of Number of Positives
### Top 10 Counties with Number of Positive Cases
![number of cases by county top 10 trajectory states weekly average](figures/trajectory-nys-county-top-ten-log-log.png)

### Counties with at least 900 Number of Positive Cases
![number of cases by county trajectory states weekly average 900 cases min](figures/trajectory-nys-county-log-log-scatter-x-limit.png)

### All Counties in New York State
![number of cases by county trajectory states weekly average](figures/trajectory-nys-county-log-log-scatter.png)

### New York State
![nys trajectory weekly average](figures/trajectory-nys-log-log.png)  


## Time Series
### Top 10 Counties with Number of Positive Cases
![timeseries top 10](figures/timeseries-by-county-top-10.png)

![timeseries top 10 log](figures/timeseries-by-county-top-10-log.png)

### All Counties in New York State
![timeseries by county](figures/timeseries-by-county.png)

![timeseries by county log](figures/timeseries-by-county-log.png)








