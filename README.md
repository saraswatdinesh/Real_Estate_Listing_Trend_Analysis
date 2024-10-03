# Real Estate Listing Trend Analysis

As part of this project we explored the trends in the current house listings on realtor.com in the Bay area counties, to understand the trends in property types, cities showing promises from future investment perspective.

We also looked at the affordability of the cities based on the public median household income of the city. 

## Approach -

1. Identify and Gather the Data for Current Listings -
Getting the data for current listings from potential websites such as Zillow, RedFin and realtor were big contentions. We zeroed on the realtor.com due to its less complictaed website structure as well it provided the data about the historical listing prices of the property if any exists. 
This helped with the analysis approach we had in mind to identify which properties are listed at the discount or showing negative trend or no growth.

However, scrapping responsibly and avoiding bot detection was more important and hence we deployed a limited scrape and did random agents to fetch only couple of hundred properties a day. 

2. Clean and Process the data -
We did the parsing the of the downloaded json into tabular format for easier data analysis. Once we transformed all the property prices into single and tabular csv file, it was easier to do perform analysis leveraging pandas, matplotlib and plotly. 


## Summary -->


1. At  present there are good deals available in major hustling cities like San Francisco , San Jose , Oakland and Santa Rosa are seeing downward trend on the listing prices and are even sold at losses as well. 

2. Couple of cities like Fremont, Hayward, Fairfield, Walnut Creek shows a sign of high priced properties with majority of the listing are either above the previous listed prices last sold price is unavailable. 

3. Some of the cities has become unsustainable to own a property by residents. The median EMI payment is way higher then how much a most of the residents can afford at the max.
    Practically you cannot own a 4 bed property if you are earling the median income in almost all the bay area prominent cities couple of exceptions of Brentwood, Concord, Vacaville , Antioch and Vallejo.
    Some cities like Napa is viable option for only ultra rich and HNI individuals as the EMI amount needed for listed properties is higher than the median monthly income more most of the households. Same goes for San Francisco as well
    
    Similar trend continues for 3 beds as well. 
    
    2 beds seems be more affordable in most of the cities except cities like San Francisco , Napa, Oakland, San Mateo and Berkely, which is kind of expected. 
    
    1 bed and condos is what most of the households can afford at present. 
    
Looking at the price affordability as well the market is also categring to the needs by listing single family and condos which amounts around 80% of the total listings and hence explains the squeeze in the market for the single family homes. 

Cities such as Fremont with its close proximity to major hubs and high median household income is a good choice of investment as well as owership, given not many properties are listed under the last sold price. 

Refer the presentation for more insights on the project. 

Link - 

