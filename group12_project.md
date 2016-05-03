
=======
﻿
# Analysis on IRS data and relations between AGI and Mortgages
=============



# OVERVIEW:



We would like to study and make an analysis from the IRS data set and pull and predict the relationship between AGI and mortgages in USA.

We are planning to use the data of IRS from https://www.irs.gov/uac/SOI-Tax-Stats-Individual-Income-Tax-Statistics-ZIP-Code-Data-(SOI). On this data we are going to look at relations between AGI and Mortgages they take, the interest payed on them and how it in different states of America is. We are planning to cluster the results using K means clustering to see if there are can do any data analysis on data and also we are planning to add visualiztion as well to the clustering.. To see if there are any commonalities in between states and differences in between states. Classify states which are performing on a similar basis and which are preforming differently.





# DATA:

The IRS returns data was used for this project.We took Data driven of IRS from https://www.irs.gov/uac/SOI-Tax-Stats-Individual-Income-Tax-Statistics-ZIP-Code-Data-(SOI). 

We are planning to write a script to get the latest tokens and complete the authentication every time rather than storing them because linkedin auth tokens expire quickly <= 2hrs .

We are going to pull the dataset from different years from the above link and use ZIP Code data to show selected income and tax items classified by State, ZIP Code, and size of adjusted gross income.









# RESEARCH QUESTIONS:


Research dicusses and shows which of states pays higher mortgage interest per capita.

We would like to research different points like retrieve data and clean it and remove the unwanted bits.

Create explanatory graphs and see the relations between AGI and mortgage interest payed.

Preform K means clustering on this data and see which states and moving together and which are out of the pack. 

Find out any commonalities or differences in the data.



Research on the analysis on IRS data and relations between AGI and Mortgages would pull the economic status of the individuals how they are paying their taxes from different states and helps to understand the different state economic status.







# MODELS AND ANALYSIS:



We are planning our models and preliminary analyses will be performed in a Jupyter Notebook using pandas .
• k-means clustering algorithm
Data Representation

•	Matplot lob was used to represent data.
•	x- axis is AGI
•	y axis is ppm
•	Each cluster has a colour 	and each point in the graph is a state.
  


 



# CODE AND APPLICATION



 Posted the code in our GitHub repository and instructions on installation are in the README.md file at the root level.
 
 •	IRS data contained lot of data. We were interested in number of returns, state, AGI, mortgages.
•	Pandas handled null's and other issues in data.
•	Data was remodeled to and a new column was added to data frame called ppm per capita mortgage interest payed.
•	ppm = total mortgage paid/total returns
•	Clustering
•	The data was clustered into 3 clusters using k-means clustering algorithm
•	3 clusters were selected because the graphs of data showed a roughly into 3 groups






# PROJECT MANAGEMENT:



We are team of Six, Srikanth Budi, Venkateswara R Kotha, Sai Bharadwaja Uppala, Sundeep Vuyyuru, Keshava Paruchuri, Tharun Madagouni, we will be sharing our work amoung ourselves. Srikanth Tharun , & Venkateswara  took care of scripting, data analysis 	Data remodeling ,data clustering using K-means clustering algorithm  . Bharadwaja, Sundeep, and Keshava would work on testing of the results and make sure that Pandas handled null's and other issues in data and extract IRS data  where there would be some relation to mortgages paid and the location they are from and finally together we are collaborating to check the progress of the project testing. 



# PROJECT TEAM, DELIVERABLES AND CHECKPOINTS





## TEAM 

| Team member | Roles and skills | Contributions |
|-------------|-------------------------|---------------------------------------------|
| venkateswara kotha | Scripting , Data analysis |Data Analysis, Build Scripts |
| Srikanth Budi | Development , Testing | Testing, Build Scripts |
| Sai Bharadwaja Uppala | Documentation , Data Analysis  |  Data Analysis  |
| Sundeep Vuyyuru | Data Analysis, Python |  Data Analysis ,Development   |
| Kesava Parchuri | Testing, Data analysis,Documentation | Data Analysis, Test Harness; |
| Tharun Goud Madagouni | Plotting the results, Data analysis | Data Analysis, Matplot lob ; |

## DELIVERABLES AND CHECKPOINTS


| Checkpoint date | Expected Deliverable                                                          | Responsible team member(s) | Checkpoint results                                                                                                                  |
|---------------|-------------------------------------------------------------------------------|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------|
|2/12/16| Initial analysis on IRS data and relations between AGI and Mortgages.  | All team Members   | Check point 1 reached . |
|3/8/16|  Collected multiple years data from IRS i.e from 2001. We cannot upload all data as file sizes are more than 100MB which cannot be stored in Github  ,we would like to upload it google drive . So we need to write a script to pull the data online.and in process of aggregating the data and remove unwanted columns and just focus on returns. And would like to see at ways to develop visualization from the data.| All Team Members |  Uploded Inital Data to GDrive. |
| 3/20/16 | As the data set is more than 100 MB would upload it to google drive and provide the destination folder .Will also answer/update the research question depending upon the results seen in initial analysis |  Sai Bharadwaja Uppala ,Kesava Parchuri ,Tharun Goud Madagouni|  uploaded the irs file  |
| 4/3/16 | Would ensure that project code development is done and testing is done such that visualization results show up successfull .| venkateswara kotha,Srikanth Budi ,Sundeep Vuyyuru  |  Plotted the results using Matplot Lob    |
| 4/17/16 | Completed the testing and project a visualization results    |  Sai Bharadwaja Uppala,Kesava Parchuri ,Tharun Goud Madagouni  |       The data was clustered into 3 clusters using k-means clustering algorithm     |                 |  
| 05/01/16 |Documentaed the results and complete project   | All Team Members |     Our results show that , California is in a cluster which has more ppm Arizona is in the middle and North Dakota is part of the cluster which has least ppm.      |






