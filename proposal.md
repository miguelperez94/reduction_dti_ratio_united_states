Title: An analysis at the US state and county level about the reduction of the 
    debt-to-income ratio between 2007 and 2017 and potential implications

Name of author: Miguel Pérez Rodríguez

Subject area of choice: Using mainly data about (a) county level of the
    household debt-to-income and (b) average personal income per county, and
    taking into consideration the huge reduction at the national level of the
    debt-to-income ratio between 2007 (1.24) to 2017 (0.95), I want
    to analyze and show visually the following points: 
        (i) how was this change of deb-to-income ratios by state and county 
            level (in part to highlight which states and counties had the biggest 
            changes between 2007 and 2017), 
        (ii) see relationships between average income and debt-to-income ratios
            among counties (for example, see if poorer or richer counties were the ones 
            that have the biggest impacts of the reduction of the debt household), 
            and 
        (iii) see if there are any correlational impact between changes in
            reductions of debt-to-income ratios and other outputs at a county or
            state level, such as unemployment rates, net migration, educational
            outcomes, or crime rates, among others (this third point is still 
            under review and will be assesed depending the results on the first
            two points)

Likely data sources: Here I show the databases that I know that I will probably use,
    it is worth noting that for my third point (how reductions of debt-to-income 
    ratios correlates with other outputs) maybe I will use another additional 
    databases depending on the findings of points (i) and (ii).

    (a) Federal Reserve: County-Level Household Debt-to-Income Ratio:
        (i) URL: https://www.federalreserve.gov/releases/z1/dataviz/household_debt/county/map/#state:all;year:2024
        (ii) Description: Ratio of household debt (from FRBNY Consumer Credit Panel/Equifax Data)
            and household income (from the Bureau of Labor Statistics). Due to 
            confidentiality, the data is in ranges (not an specific point, 
            but a range between a minimum and a maximum), so I would use the average 
            of the middle point of the range for 12 consecutive quarters
            to have a more precise metric (for 2007: average of 2007 to 2009, 
            for 2017: average of 2017 to 2019).
        (iii) Estimate of how many rows/columns: I estimate that this dataset
            will give me one observation for each county and state for years 2007
            and 2017, so this would be 2 columns (county/state and debt-to-income ratio)
            and approximately 6,400 observations (3,200 counties plus states, two times each).
    
    (b) Bureau of Economic Analysis (BEA): Annual personal income by county (CAINC1)
        (i) URL: https://apps.bea.gov/regional/downloadzip.htm
        (ii) Description: Annual personal income per capita by county
        (iii) Estimate of how many rows/columns: One observation for each county 
            and state for years 2007 and 2017, so this would be 2 columns 
            (county/state and personal income) and approximately 6,400 
            observations (3,200 counties plus states, two times each).
    
    (c) U.S. Bureau of Labor Statistics: Unemployment rate by county
        (i) URL: https://www.bls.gov/lau/tables.htm#cntyaa
        (ii) Description: Unemployment rate by county, annual average
        (iii) Estimate of how many rows/columns: One observation for each county 
            for years 2007 and 2017, so this would be 2 columns 
            (county and unemployment rate) and approximately 6,300 
            observations (3,150 counties, two times each).
    
    (d) U.S. National Science Foundation: Mathematics and science proficiency 
        (i) URL: https://ncses.nsf.gov/indicators/states/indicators
        (ii) Description: Proportion of a state's fourth or eight grade public 
            school students that met or exceeded the proficiency standard in 
            mathematics o science, by state and year.
        (iii) Estimate of how many rows/columns: Four observations for each state
            for years 2007 and 2017, so this would be 5 columns (state, fourth
            and eight grade mathematics and science proficiency) and approximately
            102 observations (51 states, two times each).

Questions for professor/TA: Regarding the use of my main database (County-Level 
    Household Debt-to-Income Ratio), as I mentioned before, due to confidentiality,
    I have it only in ranges, but I expect that using an average of 3 years (12
    consecutive quarters) of the medium point of the range will give me a
    precise enought value for each observation. Is it ok for this project 
    to do the analysis following this assumption? (This would be the main assumption 
    of the data for the project). Thank you in advance.