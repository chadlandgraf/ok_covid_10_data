covidtable.csv

Stores COVID case data by county in Oklahoma. Data collection started on March 20, 2020 and ended November 3, 2021. Unless otherwise noted, all of the data is from the Oklahoma State Department of Health's situation updates. OSDH reported COVID-10 case data daily, excluding some holidays, from March 20, 2020 to March 16, 2020. They switched to a weekly reporting cadence starting on March 24, 2021. County-level reporting ended on November 3, 2021. Field descriptions:

	DATE -> Date of case report. (date)
	
	FIPS -> Federal Information Processing System (FIPS) code for county (string)
	COUNTY -> Name of county. (string)
	CASES -> Number of cumulative cases of COVID-19 reported in county. (number)
	DEATHS -> Number of cumulative deaths due to COVID-19 reported in county. (number)
	RECOVERED -> Number of cumulative recovered cases of COVID-19 reported in county (number)
	POPULATION -> County population. Prior to 10/27/21, population was from US Census Bureau American Community Survey 5-year Data. After 10/27/21, population was from US Census Bureau 2020 Decennial Population. (number)
	CS_RATE -> Cumulative cases of COVID-19 per 100,000 population. (number)
	DTH_RATE -> Cumulative deaths due to COVID-19 per 100,000 population. (number)
	REC_RATE -> Cumulative recovered cases of COVID-19 per 100,000 population. (number)
	SOURCE -> Data source. Oklahoma State Department of Health (OSDH). (string)
	NCHS -> 2013 NCHS Urban–Rural Classification Scheme for Counties description for county. (string)
	ACTIVE -> Number of active COVID-19 cases in county. Calculated by subtracting number of deaths and recovered cases from reported cases. (number)
	NEW_CASES  ->  Number new cases of COVID-19 reported. Calculated by subtracting the number of cumulative cases on any given day from the number of cumulative cases reported on the previous day. (number).
	
NEW_DEATHS  -> Number new deaths due to COVID-19 reported. Calculated by subtracting the number of cumulative deaths on any given day from the number of cumulative deaths reported on the previous day. (number).

NEW_CASES_MA  ->  7-day moving average of new COVID-19 cases. (number)

ACT_RATE -> Number of active COVID-19 cases in county per 100,000 population (number)


covidtable.csv

Stores COVID case data by ZIP Code Tabulation Area (ZCTA) in Oklahoma. Data collection started on February 2, 2021 and ended November 3, 2021. Unless otherwise noted, all of the data is from the Oklahoma State Department of Health's situation updates. OSDH reported COVID-10 case data daily, excluding some holidays, from February 2, 2021 to March 16, 2020. They switched to a weekly reporting cadence starting on March 24, 2021. ZIP code-level reporting ended on November 3, 2021. Field descriptions:

	Zip -> ZIP code. (string) 
	Cases -> Number of cumulative cases of COVID-19 reported in ZIP code. (number)
	Deaths -> Number of cumulative deaths due to COVID-19 reported in ZIP code. (number)
	Recovered -> Number of cumulative recovered cases of COVID-19 reported in ZIP code. (number)
	ReportDate -> Date of case report. (date)
	TOT_POP -> ZIP code population. Population is from US Census Bureau American Community Survey 5-year Data. (number) 
	CS_RATE -> Cumulative cases of COVID-19 per 10,000 population in ZIP code. (number)
	DTH_RATE -> Cumulative deaths due to COVID-19 per 10,000 population in ZIP code. (number)
	Active -> Number of active COVID-19 cases in ZIP code. Calculated by subtracting number of deaths and recovered cases from reported cases. (number)
	ZCTA -> Corresponding ZIP Code Tabluation Area for reported ZIP code. (string)
	ACT_RATE -> Number of active COVID-19 per 10,000 populationin ZIP code. (number)
