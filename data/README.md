# data

This folder contains the data for the analysis found in "Spatial Regression Analysis of Poverty in R" (2019) by Kamenetsky, Chi, Wang, and Zhu *([Spatial Demography](https://link.springer.com/article/10.1007/s40980-019-00048-0))*. Supplementary tutorials can be on the GitHub pages site found [here](https://mkamenet3.github.io/SpatialRegPovertyR/).

Due to the size of the shape files, please contact maria.kamenetsky@gmail.com directly for them.
  
The variable of interest is poverty (*povty*), measured as the percentage of
individuals age 18-64 living in poverty in a county in year 2000. We include
a set of economic, social, and demographic factors that may relate with county-level poverty rates. Specifically, three variables, agriculture (*ag*), manufacturing (*manu*), and retail (*retail*), are the percentages of workers in the agricultural sector, the manufacturing sector, and the retail sector, respectively. For socially-related factors, *foreign* is the percentage of the foreign-born population in a county and female employment (*feemp*) is the percentage of female employment in the total population. Human capital stock is captured by high school (*hsch*), which indicates the percentage of the population that completed a high school education. Lastly, we use percentage Blacks (*black*) and percentage Hispanics (*hisp*) to capture racial and ethnic compositions. These variables are measured in 2000 based on the Decennial Census data. While other variables have been used in poverty research, in this manuscript we focus on these selected variables for the purpose of illustrating spatial regression modeling for poverty research in R.
 

## Files
 
- ```uspoverty2000.csv```: csv file with key demographic variables (above)

For the supplementary tutorials, we also provide ```supplement_poverty.csv```.
The shape files required for the `tmap` tutorial will be available soon. Users
can create them locally on their machine by first running the `Weighting and
Transformations` tutorial in the `supplementary` folder.
