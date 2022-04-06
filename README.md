# Purpose

The purpose of this project is to visually show the current market presence of a company on maps that I created using various R packages, particularly leaflet, leaflet.extras. Also, to use API to retrieve U.S. Census Bureau data to identify potential white space opportunities based on given M&A criteria. 

I hope this project will be useful during the M&A pre-screening stage to find a list of potential targets that fit within the buyer's strategic M&A rationale - whether that is acquiring another company within the identified location(s) or planning out a de-novo development. 

# Key Findings

This project focused on Brookdale Senior Living, which is one of the largest senior living providers in the U.S. Some of the key findings I found: 
- in the past years, Brookdale closed 25 facilities spanned across 4 states - WA, TX, Washington D.C., and CA
![closed facilities](https://github.com/qinggao68/Project-1-Market-Expansion-Analysis/raw/main/closed_facilities.PNG)
- Brookdale still has 751 facilities and has the most market presence in TX, FL, and CA with 141, 92, and 79 open facilities, respectively 
![still open facilities](https://github.com/qinggao68/Project-1-Market-Expansion-Analysis/blob/main/opened_facilities.PNG)
- I discovered there are 14 states that Brookdale has yet any market presence, they are: "AK", "HI", "IA", "ME", "MI", "MS", "NV". "NH". "NM", "ND", "OR", "PA", "SD", and "VT"
- conducted in-depth market research and found that OR is one of the fastest-growing states that has an increasing number of older adults
![elder pop. in OR by county](https://github.com/qinggao68/Project-1-Market-Expansion-Analysis/blob/main/Elders_Population_by_County.PNG)
- then I found that Multnomah County and Washington County have the highest projected elderly population in 2019
 
![proposed locations](https://github.com/qinggao68/Project-1-Market-Expansion-Analysis/blob/main/Proposed_Locations.PNG)
# Additional Information
In my analysis, the dataset that I found on the Homeland Infrastructure Foudation-Level is not up-to-dated. As of now, Brookdale has already expanded into the proposed state that I recommended in my project, which is Oregon. And, the numbers of both closed and still open facilities may also not been up-to-dated. 

This project may serve more purpose for the healthcare sector, particularly companies whose M&A strategic rationale center around the growth rate of population, wealth income, % of insured, proximity to existing locations for chairside opportunities, and access to major hospital connection.

# Project Scope 
1. Examine the dataset 
2. Examine and map out the closed locations
3. Examine the numbers of existing locations 
4. Remove closed locations
5. Map out the existing locations on a heatmap 
6. Identify which states the company has market presence vs states with no market presence 
7. Conduct initial market research based on the company's M&A strategic goals 
8. utilized these market research findings to pull data from the U.S. Census Bureau using tidycensus and censusapi packages 
9. Map out the census data 
10. Proposed new market opportunities based on the company's strategic rationale(s)
11. Map out the open and recommended locations 

# Future Work
I plan to deploy the outputs on Shiny server, currently working on the app. 

# References
[Homeland Infrastructure Foundation-Level Data (HIFLD) database - Nursing Homes] https://hifld-geoplatform.opendata.arcgis.com/datasets/geoplatform::nursing-homes/about

[Leaflet for R] https://rstudio.github.io/leaflet/choropleths.html

