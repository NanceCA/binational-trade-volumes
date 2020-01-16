# Exploring Binational Trade Volumes
leveraging exploratory data analysis and machine learning algorithms to extract insights on the binational trade relationship between Mexico and the United States

## Why explore binational trade volumes between Mexico and the United States?

Trade is an integral part of the relationship between Mexico and the United States and as shown by the chart below, sourced with data from the US International Trade Commission, general Imports from Mexico to the US have been increasing over time.

Leveraging EDA and machine learning algorithims on this data can help provide greater insight into understanding if increased trade also catalyzes increased movement of people between both countries, as an indicator of a growing MX-US relationship. This claim depends on two key hypothesis:

1. Between two countries, whether that is tourism, permanent residency, or temporary residency can increase mutual understanding binationally
1. Increased trade between two economies can cause both parties to experience mutual economic gain thereby incentiving both countries to continue trading

**General Imports from Mexico to the United States over time in (billions)**

![image](https://user-images.githubusercontent.com/48306129/72568970-20702580-386e-11ea-81f8-0b0fccdc2e48.png)

By quantifying US/MX trade and US/MX mobility data, I attempt to understand if these are two indicators of the current state of the MS/US relationship. Using a Random Forests algorithim, can further explore the granuality of trade and mobility trends. 

Subquestions this exploration pursues includes the following:

Field | Additional Project Question
------------ | -------------
Trade | Though trade volume has increased, how have specific commodities changed over time?
Economic Gail | Where do the economic benefits go?
Binational Environment | For lower peaks in trade volumes, what political, social, or economic dynamics were occurring at the time?


What can this increase in transactions and interactions tell us about the economic benefits that both countries may experience? Can trade volumes be an indicator of increased binational exchange? Lastly, can understanding trade volumnes give us insight into how the current state of the MX/US relationship?

## Key datasets
The US Internnational Trade Commission has publically accessible data to review trade volumes in depth. THe US International Trade Commission leverages datasets included in this repository are specific to import and export transactions between Mexico and the United States. 

World Trade Organization (WTO) data is also included in the respository.

See some of the queries of interest that I've pursued below:

### US International Trade Commission

**Total Exports** in the following query is defined as the total number of goods exported from the United States to Mexico.  
```
    Trade Flow: Total Exports
    Classification System: HTS (Harmonized Tariff Schedule) Items
    Years to Report: 1997 - 2018 (Current)
    Countries: Mexico `
 ```

 
**Imports for Consumption** in the following query is defined as the total number of goods imported from Mexico that were labeled as for immediate consumption from the United States to Mexico.
 
 ```
    Trade Flow: Imports for Consumption
    Classification System: HTS (Harmonized Tariff Schedule) Items
    Years to Report: 1997 - 2018 (Current)
    Countries: Mexico `
 ```
  
**Domestic Exports** in the following query is defined as the total number of goods manufactured in the United States or originated from another country but altered in the United States and exported to  Mexico.
 
  ```
    Trade Flow: Domestic Exports
    Classification System: HTS (Harmonized Tariff Schedule) Items
    Years to Report: 1997 - 2018 (Current)
    Countries: Mexico `
 ```

 ### Leveraging a Random Forest Algorithim to understand the relationship between binational trade and tourism 

 _What are random forests?_

 A random forest is one of many supervised learning algorithims that is leveraged to predict an outcome. It can be either a regression or a classification depending on the type of data, continuous or categorical, respectively.

 Random forests are composed of decision tree models.

 #### Why Random Forests to understand trade volumes?

 Trade volumes correlated with another variable can provide insight into key indicators that may describe a binational relationship.   

