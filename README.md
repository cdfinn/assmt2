# assmt2
For adv data S25

Analysis of Revised 2020-2024 NYC Borough Labor Force Data
This repository contains the raw data from NY State Dept of Labor on the New York City region employment rates by borough and my analysis using Google Sheets

# Data
This analysis uses "Revised 2020-2024 Borough Labor Force Data" spreadsheets.

The spreadsheets come from: https://dol.ny.gov/labor-statistics-new-york-city-region

Name of source: NY Department of Labor
[link](https://dol.ny.gov/statistics-revised-2020-2024-borough-labor-force-data): Raw data of employment numbers by borough 2020–2024
Each of the spreadsheets contain, among others, the following columns relevant to the analysis:

Labor Force — Population of elgible workers in each borough, each month from 1/2020 to 12/2024
Employed - Employed population in each borough, each month from 1/2020 to 12/2024
Unemployed	- Unemployed population in each borough, each month from 1/2020 to 12/2024
Unemployment Rate - Percentage of unemployed eligible workers in each borough, each month from 1/2020 to 12/2024

# Methodology
Using Google Sheets, I performed the following analyses:

Step 1: Create "NYC-Wide" tab that summarizes data from all 5 boros				
	"=sum' function of Labor Force, Employed and Unemployed numbers across all 5 borough data sheets			
	"=average' function of unemployment rate across all 5 borough data sheets			
	I now have a baseline to compare each borough's data to the city as a whole as well as borough-by-borough comparisons			
				
Step 2: Finding trends in how different boroughs fared in the pandemic				
	comparing 2020 and 2024 yearly averaged data in each borough 			
	comparing month with highest and lowest unemployment rate in each borough, month with highest and lowest labor force population, and Jan 2020 vs Dec 2024			
		using "=min" and "=max" functions to find the highest and lowest values in a given column		
		attempted to use VLOOKUP to fill out corresponding M, Y and labor force population columns for each, but kept getting errors with VLOOKUP and had to manually enter data		
	comparing Jan 2020 vs Dec 2024			
		(only Staten Island has ever recovered to Jan 2020 pre pandemic employment rate. Staten Island had a 4.0% unemployment rate in both 1/2020 and 4/2024. The borough ended 2024 with a 4.6% unemployment rate)	


# Output
A linked .csv filed in this repository contains a summary of my analysis in a single spreadsheet
The full (and messy) Google Sheets file where I conducted my analysis can be found here, including a data diary: https://docs.google.com/spreadsheets/d/1FvhgOoe950-9o0ten1CsJWdOrdUx7gy6rE_aNxx2aKE/edit?usp=sharing

Running the analysis yourself:
You can run the analysis yourself using Google Sheets and standard functions

Feedback / Questions?
Contact Charlie Finnerty at charliefinnerty01@gmail.com
