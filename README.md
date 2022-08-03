# Surfs_up 

## Module 9 Challenge ~ Surf's Up with Advanced Data Storage and Retrieval
---
## Overview of Project
In this module, we will explore the differences between SQLite and PostgreSQL databases. Using our knowledge of Python, Pandas functions and methods, and SQLAlchemy, I will use SQLAlchemy to connect to and query a SQLite database called hawaii.sqlite. And then, I will filter the date column of the Measurements table to retrieve all the temperatures for the months of June and December. From there, convert those temperatures into a list, create a DataFrame from the list, and generate the summary statistics.
### Purpose
W. Avy would like more information about temperature trends in Oahu, Hawaii before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the Surf and Ice Cream shop business is sustainable year-round. 

---
**Deliverable 1 & 2 ~ Determine the Summary Statistics for June & December**

**Referring to... _SurfsUp_Challenge.ipynb_ file** 
### Summary Statistics for Month of June between 2010-2017

<img width="150" alt="June_temps" src="https://user-images.githubusercontent.com/68654746/182716943-fa729474-9dae-408c-8f70-2dfaed47c182.png">

![june_temp_plot](https://user-images.githubusercontent.com/68654746/182719735-c5095214-b577-4b0d-a08e-f0dd6cec420d.jpg)

### Summary Statistics for Month of December between 2010-2016

<img width="173" alt="Dec_temps" src="https://user-images.githubusercontent.com/68654746/182717370-b4495ce9-78dc-401c-9978-14002b1aa304.png">

![dec_temp_plot](https://user-images.githubusercontent.com/68654746/182718912-207e58f7-a31a-4c2e-8f70-13d4930b5a48.jpg)

### RESULTS
- The mean temperature of 75°F for June is higher than the mean temperature of 71°F for December. \
- After plotting and grouping the data into 15 bins, the histograms illustrated how the data frequency in June and December center around the two different means. To be consist, the ranges of both axes were generated as the same for visually easier comparison of the descriptive statistics between the months. June appears to have a slight left skew, where December is more symmetrical.
- However, the opposite is true for precipitation. December had the higher precipitation of .22 inches while June had .14 inches.

![june_prcp](https://user-images.githubusercontent.com/68654746/182716982-9080c9c7-3a6c-4d70-8b87-44ff242a5fa7.jpg)

![june_prcp_scatter](https://user-images.githubusercontent.com/68654746/182719157-a427806b-4b73-46a9-89c5-c37dc3da865d.jpg)

![dec_prcp](https://user-images.githubusercontent.com/68654746/182717400-5dac81ef-f98f-4df3-9103-9484b029d08c.jpg)

![dec_prcp_scatter](https://user-images.githubusercontent.com/68654746/182719134-1e09dd5a-2b73-4b85-a24a-ce69a1f50b0c.jpg)

---
**Deliverable 3** ~ Summary**
