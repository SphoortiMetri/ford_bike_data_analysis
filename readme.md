# Ford GoBike System Data Analysis
## by Sphoorti Metri


## Dataset

The dataset consists of Bay Wheels's trip data. It has 1732358 entries and 16 features. It has data about bike riders age, gender, start_time, station_name, etc.The dataset can be found on Ford GoBike website.(https://s3.amazonaws.com/fordgobike-data/index.html). I downloaded 2018 data from the website and stored them in corresponding comma separated files. I combined them into a single dataframe for further analysis

## Summary of Findings

Based on information in this dataset, bay wheel's bikes usage is highest in the month of October. Throughout 2018, men have used these bikes more than any other gender. Peak hours of the day are 8:30 AM and 5:30 PM. Mornings and afternoons are the busiest time of the day. Duration of the trips are longest during the night. Subscribers are more in number when compared to customers, whereas average trip duration of customers are longer for customers' bike rides. age_group_1(18 to 40 years old) have been consistently a larger portion of users.

## Key Insights for Presentation

Feature engineering from existing features to extract more information resulted in better analysis and understanding of the dataset. I focused on features influencing the increasing number of bike rides over time. I explored data visually in terms of univariate, bivariate and multivariate plots

## What do I need to install?
- NumPy
- pandas
- Matplotlib
- Seaborn
