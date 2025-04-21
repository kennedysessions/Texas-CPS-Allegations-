# Texas-CPS-Allegations-
This repository contains data, analytic code, and findings that support portions of the article, “Texas Reports Nine-Year Low in CPS Allegations,” published April 20, 2025. Please read that article, which contains important context and details, before proceeding. 

Data
This analysis uses one spreadsheet containing claims from the Texas Department of Family Protective Services, which tracks how many cases of child abuse were made in Texas’s 254 counties. The spreadsheet comes from the following sources:

- Texas Department of Family and Protective Services:
investigation.sheets: Raw data of claims from 2014 to 2024

Each of the spreadsheets contain, among others, the following columns relevant to the analysis:

- Fiscal Year — The year the claim was filed
- County — The county where the alleged abuse was reported
-Region– What region the claim was made in 
-Type of Allegation- what type of abuse category was it filed under 
-Allegation Count 

Methodology

The notebook (notebooks/texascpsproject) performs the following analyses:

Part 1: Finds the number of CPS complaints per year since 2015
Calculates the number of Texas CPS abuse claims by year 
Finds the average of claims filed by year 
Calculates the number of allegations per county 
Calculates the type of allegations per county and region 

Outputs

The results are saved as: texascpsproject.ipynb).

Running the analysis yourself

You can run the analysis yourself. To do so, you'll need the following installed on your computer:
- Python 3

Licensing

All code in this repository is available under the MIT License. The data file in the output/ directory is available under the Creative Commons Attribution 4.0 International (CC BY 4.0) license. All files in the data/ directory are released into the public domain.

Feedback / Questions?

Contact Kennedy Sessions at k.sessions76@journliasm.cuny.edu. 

