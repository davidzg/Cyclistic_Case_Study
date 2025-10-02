# Cyclistic_Case_Study

## Introduction
This is the final project for the Google Data Analytics Professional Certificate.

This project follows the data analysis process phases:
- ❓ Ask
- 🧰️ Prepare
- 🛠 Process
- 📢 Share
- 🚀 Act

The project has been developed in R, please refer to the [Rmd file](Cyclistic.Rmd) for more details.

You can download the [HTML output file](Cyclistic.html) to see the full analysis with results and visualizations.

## Problem description
The primary objective of this analysis is to determine how casual costumers are using **Cyclistic** (a fictional bike-share company) bikes compared to subscribed members, in order to design a new marketing strategy that will focus on converting casual riders into annual members.

### Data set used for this project
The [data](https://divvy-tripdata.s3.amazonaws.com/index.html) has been made available by Motivate International Inc. under this [license](https://divvybikes.com/data-license-agreement).

You can also use a reduced dataset. you can download the [Zip file](./data/reduced_data.zip) and extract the csv file before imprting the dataset into the project.

### Data filed skills displayed
 - Reading multiple files into a single dataset
 - Formating data
 - Cleaning data
 - Filtering data
 - Grouping data
 - Visualising data


## Results

### Insights
1. Casual users ride in average 28% less than users with a membership
2. Casual users ride in average 2.2 times more than users with membership.
3. Electric bikes are slightly more popular than classic bikes for casual users, while the opposite is true for users with annual membership.
4. Casual users use *cyclistic* bikes with more frequency during the weekends, but still it is less than users with a member ship.
5. Regardless the day of the week, casual users ride in average longer than members. The ride duration is higher during the weekends.
6. Average ride length for Member users during week days is constant (close to 13.13 minute overall average), suggesting that members use the bikes as a mean of transportation to ride fixed distances, for instance committing to work or school.
7. Spring and Summer are the seasons with most number of rides for both types of users.
### **Recommendations**
- To run the user conversion campaigns during the weekends, specially on Saturdays, where most of the casual users are using the *Cyclistic* bikes.
- Spring and Summer are the seasons where most users, casual and members, use *Cyclistic* services. It is the best time to do the marketing campaign outside and close to the stations.
- As casual users make longer bike rides for leisure on average, the campaign should put emphasis on:
  - The benefits of a membership from a cost per minute perspective compared to the single casual use. 
  - The reduced cost for electric bikes compared to the single casual cost.
  - The benefits of using the bike as a regular mean of transportation, not only to keep healthy habits, but also for economic reasons.

### **Further Analysis**
It would be worthy to spend time analyzing the stations and their closeness to places of interest and see the difference between casual and membership users. 