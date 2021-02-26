# surfs_up
## Overview of the project 

W. Avy likes your analysis, but he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

That's said, we want to review the  weather patterns in Hawaii as we look to open a surf and ice cream shop. 
This project focused on the weather temperature in June and December, looking at different statistics between the two periods to help assess whether an ice cream/surf shop would have good weather conditions in which to operate.

## Resources:

- Data : [hawaii](/surfs_up/hawaii.sqlite)
- Software : Python (jupyter notebook, pandas, matplotlib), VS CODE, SQLAlchemy (ORM queries), Flask.

## Results 


### Deliverable 1

In this deliverable, we filtered the date the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of **June**, then we convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics.

June results showed as the following:

![june_temperature_statistics](/Resources/june_temperature_statistics.PNG)


### Deliverable 2


In this deliverable, we filtered the date the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of **December**, then we convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics.


December results showed as the following:

![December_temperature_statistics](/Resources/December_temperature_statistics.PNG)



## Summary and Analysis:

- The three major pointsthat we can pull from the two analysis deliverables:

  1- Average temperature between June and December is 75 and 71 degrees respectively, showing a moderate temperature and a little fluctuation between the two periods from an average standpoint.
  2- the maximum temperatures of 85 (June) and 83 (December) are also remarkable similar.
  3- the minimum temperature of 56 (December) and 64 (June) show the greatest variance, and reflects a much lower temperature level in December that may not be conducive to ice cream or surfing. However, with standard deviations of 3.25 (June) and 3.74 (December) we would expect a little more variation in the december numbers.
  
  
