This notebook was created as the accompaniment to a written assignment for Boston College's Project Management in Machine Learning's group assignment two. The two contributors to this assignment are Matthew O'Connor and Christina Wright.
Running this ipynb notebook requires the AirlineData.csv file that is listed here and a second much larger file that is not listed here. The larger file is available on the internet at https://data.transportation.gov/Aviation/Consumer-Airfare-Report-Table-6-Contiguous-State-C/yj5y-b2ir/about_data 
The first half of this notebook runs a series of cleaning algorithms that cleans the initial data file from the Department of Transportation, takes only the data from 2021 or later, and does things relevant to this project like separating the city from the state and splitting the coordinates into two numerical columns
At the end of the first half there was code to generate a file called AirlineData.csv. I have taken it out and simply included AirlineData.csv myself. Thus, the first half of the code is provided to show the data cleaning process as this is an assignment
The second half of this assignment takes in AirlineData and combines it with a file that shows the average temperature of different cities. It then runs the same algortihms as the first half
We can see that adding the average temperatures of the cities does not do much by running the decision tree classifier before and after
There is also commented out code to run a support vector machine. You can attempt to run it if you want but the files are very large and it would be tough to do on Colab due to the cloud based nature of it.

Note that for sections of this code, the built in AI tool in colab was used to generate a section of code and then I edited it to ensure accuracy when it went wrong. Some of the comments are AI generated

https://www.globalair.com/airport/region.aspx
https://en.wikipedia.org/wiki/Fuel_economy_in_aircraft#Example_values

The 40 dollars per mile is a rough estimate that takes into account the average burn rate and the cost of jet fuel. If we were a real airline, we would have access to far more industry data to build a better model.
