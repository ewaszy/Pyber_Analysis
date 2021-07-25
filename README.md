# Pyber_Analysis

## Purpose 
The purpose of this project is to learn how to create and modify line, bar, scatter, bubble, pie, and box-and-whisker plots using Matplotlib as well as how to determine the mean, median, and mode of a dataset using Pandas, NumPy, and SciPy statistics.

To perform the analyses, I used Jupyter Notebook and Pandas to inspect data, merge datasets, perform calculations, and create data series and data frames from CSV files. The secondary analysis introduced the pivot() and resample() commands. 

## Overview
The intial analysis consisted of importing two sets of data into a Pandas DataFrame, merging the dataframes, and creating a bubble chart that showcases the average fare versus the total number of rides with bubble size based on the total number of drivers for each city type, including urban, suburban, and rural. Statistics for each city type were calculated from the data. Then, box-and-whisker plots were created to identify outliers in the data. Finally, pie charts were created to illustrate the percent of total fares, total rides, and total drivers for each city type. 

In the secondary analysis, the same two CSV files from the inital analysis were imported and merged into a DataFrame. From this DataFrame, a new summary DataFrame was created by extracting ride-sharing data by city type. The new DataFrame contatining ride-sharing data by city type was formatted, and a multiple-line graph was made to provide a visualization of how the total weekly fares differ for each city type by month. 
 
## Results
The differences in ride-sharing data among the different city types is illustrated in the new DataFrame created in the secondary analysis, as well as the multiple  created from that DataFrame. 

### Ride-Sharing Data by City Type Summary DataFrame 

![image](https://user-images.githubusercontent.com/84869167/126914059-3766f809-7b32-4459-b5d6-a9075470c30d.png)

### Multiple-line Chart 

![image](https://user-images.githubusercontent.com/84869167/126914073-02ddc34b-4367-4a7a-85b4-afd50fc38599.png)

### When looking at these illustrations, we can see that:  

* Urban citites have the most total rides, total drivers, and total fares. Urban cities have the lowest average fare per ride as well as average fare per driver. 

* The total number of rides, drives, total fares, and average fare per ride and per driver for suburban cities falls between ubran (highest) and rural (lowest) citites.

* Rural citites have the least total rides, total drivers, and total fares. Rural cities have the highest average fare per ride as well as average fare per driver. 

* Based on this information, we can infer that less rides occur in rural cities, but the trips cover longer distances. The majority of rides occur in urban citites, but are shorter in distance. 

## Summary
Based on the results, I would provide these recommendations to the CEO for addressing the disparities between urban and rural city types:
* Decrease the cost per mile for rural cities, increase the cost per mile in urban cities. 
* Provide incentives/rewards/discounts for customers for sharing thier ride with another person(s). By sharing a ride with someone, the cost of a long distance ride can be split, making it more affordable for customers to utilize the service without compromising the total cost of the ride (driver incentive). 
* Create a minimum distance requirement for urban cities. 
