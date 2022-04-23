# Purpose

The purpose of this project is to visually show the current market presence of a company(Brookdale Senior Living) on maps that I created using various R packages, particularly leaflet, leaflet.extras. Also, to use API to retrieve U.S. Census Bureau data to identify potential white space opportunities based on given M&A strategic rationale(s). 

I hope this project will be useful during the M&A pre-screening stage to find a list of potential targets that fit within the buyer's strategic M&A rationale - whether that is acquiring another company within the identified location(s) or planning out a de-novo development. 

# Key Findings

I designed and built a web application to showcase my analysis. 

The link to the app is: https://christina-gao.shinyapps.io/Brookdale-Senior-Living-Market-Expansion-App/

Please see the screenshots and a brief summary of what I did in each step: 

1. tab 1 - facilities
- mapped out Brookdale Senior Living's numbers of facilities, found they have a total of 776 facilities
- closed 25 facilities that spanned across 4 states - WA, TX, Washington D.C., and CA 
- still have 751 open facilities(at the time of this analysis) 
- found that Brookdale has the most market presence in TX, FL, and CA with 141, 92, and 79 open facilities, respectively 
![facilities stats](https://github.com/qinggao68/Project-1-Market-Expansion-Analysis/blob/main/open%20facilities%20vs%20closed%20facilities.PNG)

2. tab 2 - Heatmap of OR's elderly population 
- I discovered there are 14 states that Brookdale has yet any market presence, they are: "AK", "HI", "IA", "ME", "MI", "MS", "NV". "NH". "NM", "ND", "OR", "PA", "SD", and "VT"
- then I conducted in-depth market research and found that OR is one of the fastest-growing states that has an increasing number of older adults
![elder pop. in OR by county](https://github.com/qinggao68/Project-1-Market-Expansion-Analysis/blob/main/heatmap%20of%20OR%20elderly%20pop..PNG)

3. tab 3 - Proposal of two potential white-space opportunities
- I used tidycensus package to API US Census data and found that Multnomah County and Washington County have the highest projected elderly population in 2019
- then I mapped out these two locations with surrounding states' market presence  
![proposed locations](https://github.com/qinggao68/Project-1-Market-Expansion-Analysis/blob/main/proposed%202%20areas.PNG)

4. tab 4 - Dynamic and interactive data table
- I built a dynamic data table that allow filtering 


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

# References
[Homeland Infrastructure Foundation-Level Data (HIFLD) database - Nursing Homes] https://hifld-geoplatform.opendata.arcgis.com/datasets/geoplatform::nursing-homes/about

[Leaflet for R] https://rstudio.github.io/leaflet/choropleths.html

[Tidycensus] https://walker-data.com/tidycensus/articles/basic-usage.html
