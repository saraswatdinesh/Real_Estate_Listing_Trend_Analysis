# Real Estate Listing Trend Analysis

As part of this project, we explored the trends in the current house listings on realtor.com in the Bay area counties, to understand the trends in property types, and cities showing promises from a future investment perspective.

We also looked at the affordability of the cities based on the public median household income of the city. 

## Approach -

**1. Identify and Gather the Data for Current Listings -**
Getting the data for current listings from potential websites such as Zillow, RedFin and realtor were big contentions. We zeroed in on realtor.com due to its less complicated website structure and it provided data about the historical listing prices of the property if any exists. 
This helped with the analysis approach we had in mind to identify which properties are listed at a discount or showing a negative trend or no growth.

However, scrapping responsibly and avoiding bot detection was more important and hence we deployed a limited scrape and did random agents to fetch only a couple of hundred properties a day. 

**2. Clean and Process the data -**
We did the parsing of the downloaded JSON into a tabular format for easier data analysis. Once we transformed all the property prices into single and tabular CSV files, it was easier to perform analysis leveraging pandas, matplotlib, and plotly. 


## Summary -->


1. At  present there are good deals available in major hustling cities like **San Francisco, San Jose , Oakland and Santa Rosa** are seeing the **downward trend** in the listing prices and are **even sold at losses** as well. 

2. A couple of cities like **Fremont, Hayward, Fairfield, and Walnut Creek** show a sign of high-priced properties with the majority of the listings either above the previously listed prices last sold price being unavailable. 

3. Some of the cities have become unsustainable to own a property by residents. The median EMI payment is way higher than what residents can afford at the max.
    **Practically you cannot own a 4-bed property if you are earning the median income in almost all the Bay Area prominent cities** couple of exceptions Brentwood, Concord, Vacaville, Antioch, and Vallejo.
    Some cities like **Napa** are viable options for only **ultra-rich and HNI individuals** as the EMI amount needed for listed properties is higher than the median monthly income of most of the households. The **same goes for San Francisco** as well.
    
    A similar trend continues for 3 beds as well. 
    
    **2 beds seem to be more affordable** in most of the cities **except** cities like **San Francisco, Napa, Oakland, San Mateo, and Berkeley, which is kind of expected**. 
    
   **1 bed and condos is what most of the households can afford at present**. 
    
**Looking at the price affordability as well the market is also catering to the needs by listing single-family and condos which amounts to around 80% of the total listings and hence explains the squeeze in the market for single-family homes.**

Cities such as **Fremont** with its proximity to **major hubs and high median household income** are a good choice for investment as well as ownership, given not many properties are listed under the last sold price. 

Refer to the presentation for more insights on the project. 

Link - 

