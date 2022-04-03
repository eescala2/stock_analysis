# stock_analysis
VBA for Stock Analysis

Purpose of project is to use VBA to analyze stocks that were provided. There are twelve tickers in the data as well as thousands of rows of data. The goal is to look at every ticket to see the return from the total volume and is gained each year. There are two different sheets due to the different years. There was a collaborative attempt through modules to create a code, but the challenge now is to refactor the code to make it more efficient for bigger datasets. 

Findings include that the majority of tickers had a positive return and were good investments. The DQ analysis requested specifically had the best return. For 2018, returns were not as high and the volume remained low, but this is due to an increase of prices.<img width="287" alt="2017" src="https://user-images.githubusercontent.com/102098068/161453283-1f500f8c-3cf3-40e3-9b6d-f6dd1b78051c.png"><img width="333" alt="2018" src="https://user-images.githubusercontent.com/102098068/161453288-9872c185-51f2-4954-9774-f581c5e25d33.png">



Refactoring the code was essential for bigger datasets to be handled in the future. Three output arrays were created so that a loop could be created. If-statements can be used to select the ticker so each cell can be looked at for volume and return totals. Initial code only used starting price and ending price with looping of all values. In this, one loop was used including an inner and outer loop.
<img width="277" alt="Old_2017" src="https://user-images.githubusercontent.com/102098068/161453297-6edaae4d-2b28-497f-9ccd-07403a55295a.png">
<img width="268" alt="Old_2018" src="https://user-images.githubusercontent.com/102098068/161453300-6df6d76e-be85-4bf4-a104-6416df8b6870.png">

Conclusion was that the refractory code was more than half the amount of time of the previous code. This is a positive outcome and means that code is more efficient for future analysis.

<img width="275" alt="ReFactored_2017" src="https://user-images.githubusercontent.com/102098068/161453312-d3c5695e-6527-4c9f-94b1-711303df59ac.png">
<img width="276" alt="ReFactored_2018" src="https://user-images.githubusercontent.com/102098068/161453316-1518df7d-a40f-41fd-864f-8053bbb62c1f.png">
