# Exploring Binational Trade Volumes
leveraging exploratory data analysis and machine learning algorithms to extract insights on binational trade 

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

