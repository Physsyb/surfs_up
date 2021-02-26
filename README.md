# surfs_up
# Overview of the statistical analysis
> The purpose of the analysis is well defined.
#### W. Avy likes your analysis, but he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

## Resources
* Data Source: ~hawaii.sqlite`
* Software/Tools: Jupyter Notebook 6.1.4, Visual Studio Code 1.53.2, Anaconda 4.9.2, Python 3.7.9, Pandas, Matplotlib

## Deliverable 1: Determine the Summary Statistics for June 
> Using Python, Pandas functions and methods, and SQLAlchemy, you’ll filter the date column of the Measurements table in the `hawaii.sqlite` database to retrieve all the temperatures for the month of June. You’ll then convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics.
* #### A working query is written to retrieve the June temperatures from the `date` column of the `Measurement table`.
![1](https://user-images.githubusercontent.com/76136277/109354411-c355ea00-784b-11eb-81b7-4666f27c8904.PNG)
* #### The temperatures are added to a list. 
![2](https://user-images.githubusercontent.com/76136277/109354519-ebdde400-784b-11eb-93ae-c5f3ef6da070.PNG)
* #### The list of temperatures is converted to a Pandas DataFrame.
![3](https://user-images.githubusercontent.com/76136277/109354596-10d25700-784c-11eb-87f9-9f9b86174a74.PNG)
* #### Summary statistics are generated for the DataFrame. 
![4](https://user-images.githubusercontent.com/76136277/109354651-28114480-784c-11eb-8cef-b5419077d508.PNG)

## Deliverable 2: Determine the Summary Statistics for December
> Using Python, Pandas functions and methods, and SQLAlchemy, you’ll filter the date column of the Measurements table in the `hawaii.sqlite` database to retrieve all the temperatures for the month of December. You’ll then convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics.
* #### A working query is written to retrieve the December temperatures from the `date` column of the `Measurement table`.
![1](https://user-images.githubusercontent.com/76136277/109355309-0795ba00-784d-11eb-9d2c-ec48cbd949e9.PNG)
* #### The temperatures are added to a list. 
![4](https://user-images.githubusercontent.com/76136277/109361548-1c774b00-7857-11eb-8f2f-d3c0c7ff606e.PNG)
* #### The list of temperatures is converted to a Pandas DataFrame.
![3](https://user-images.githubusercontent.com/76136277/109355341-12504f00-784d-11eb-898e-68ddeba0bf2e.PNG)
* #### Summary statistics are generated for the DataFrame. 
![4](https://user-images.githubusercontent.com/76136277/109355361-18dec680-784d-11eb-81e6-ee7ce8ecbe86.PNG)

# Results
> There is a bulleted list that addresses the three key differences in weather between June and December. 
* #### The minimum temperature in June is "64 degrees" while that of December is "56 degrees".
![1](https://user-images.githubusercontent.com/76136277/109358164-534a6280-7851-11eb-8971-0d08add9d95a.PNG) ![1b](https://user-images.githubusercontent.com/76136277/109358177-56dde980-7851-11eb-86ce-9df5d76a463e.PNG)
* #### The average temperature in June is "75 degrees" while that of December is "71 degrees".
![2](https://user-images.githubusercontent.com/76136277/109358247-7248f480-7851-11eb-91a3-840dcd1e43d8.PNG) ![2b](https://user-images.githubusercontent.com/76136277/109358217-678e5f80-7851-11eb-96c7-6cfb603c0fcc.PNG)
* #### The maximum temperature in June is "85 degrees" while that of December is "83 degrees".
![3](https://user-images.githubusercontent.com/76136277/109358274-7d038980-7851-11eb-9302-2f056fa9e7f1.PNG) ![3b](https://user-images.githubusercontent.com/76136277/109358281-80971080-7851-11eb-9ced-b39b10ec6775.PNG)

# Summary
> Provide a high-level summary of the results and two additional queries that you would perform to gather more weather data for June and December.
#### Considering the results of the weather for the months of June and December mentioned above, surf and ice cream shop business is sustainable both months and year-round. Also, the Standard deviation is 3.25 in June and 3.75 in December, making a 0.5 difference between both seasons.
### Two additional weather data queries for June and December.
1. #### Number of cities in location ("Oahu")
2. #### Most popular and active city in Oahu. Having a knowledge of this will increase the chances of more visitors visiting the surf and ice cream shop, which will in turn yield more profit.
