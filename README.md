# Exploring Binational Trade Volumes & Mobilitiy Between Mexico and the United States
*Leveraging Exploratory Data Analysis (EDA) and regression to extract insights on the binational relationship between Mexico and the United States.*

## Why explore binational trade and mobility volumes between Mexico and the United States?

Trade is an integral part of the relationship between Mexico and the United States, and as shown by the chart below, sourced with data from the US International Trade Commission, commerce between Mexico and the US has increased over time.

Mobility is a also a key quantitative indicator that can provide more information about a bilateral relationship. Leveraging EDA and machine learning algorithims on trade and mobility data can help provide greater insight into understanding if increased trade also catalyzes increased movement of people between both countries, as an indicator of a growing MX-US relationship. This claim depends on two key hypothesis and one exploratory question:

1. Movement between two countries, whether that is tourism, permanent residency, temporary residency or commercial travel can increase mutual binational understanding from a social and cultural perspective 
    1. A key reason to bring in mobility data!
1. Increased trade between two economies can cause both parties to experience mutual economic gain thereby incentiving both countries to continue trading
    1. Trade is also an indicator of an existing bilateral relationship
1. If trade catalyzes economic benefits, and mobility may strengthen social and political ties, can one encourage the other?

**US-MX Imports and Exports over time in (billions)**
*Source: USITC* -
*Find these visualizations among others in the Jupyter Notebooks above*

![image](https://user-images.githubusercontent.com/48306129/77597843-53ade100-6ebd-11ea-8e6b-b54ecbf8dd2b.png)


By quantifying US/MX trade and US/MX mobility data, I attempt to understand if these are two indicators of the emerging state of the MS/US relationship (not necessarily current state in order to leverage trends over time). Both simple linear regression and polynomial regression analyses, can further explore the granuality of trade and mobility trends. 

 ### The Study Methodology, Visualizations are now hosted
 _See below for a preview of a the application_

 Click **here** to learn more.
 ![](./assets/gif.gif)

## Key datasets
The US International Trade Commission has publically accessible data to review trade volumes in depth. The datasets included in this repository are specific to import and export transactions between Mexico and the United States. 

World Trade Organization (WTO) data is also included in the respository. Data on mobility is sourced from the U.S Department of Transportation. 

See some of the queries of interest that I've pursued below. All data can be found in the dat directory of this repository.

### US International Trade Commission

**Total Exports** in the following query is defined as the total number of goods exported from the United States to Mexico.  
```
    Trade Flow: Total Exports
    Classification System: HTS (Harmonized Tariff Schedule) Items
    Years to Report: 1997 - 2019 (Current)
    Countries: Mexico `
 ```

 
**Imports for Consumption** in the following query is defined as the total number of goods imported from Mexico that were labeled as for immediate consumption from the United States to Mexico.
 
 ```
    Trade Flow: Imports for Consumption
    Classification System: HTS (Harmonized Tariff Schedule) Items
    Years to Report: 1997 - 2019 (Current)
    Countries: Mexico `
 ```
  
**Domestic Exports** in the following query is defined as the total number of goods manufactured in the United States or originated from another country but altered in the United States and exported to  Mexico.
 
  ```
    Trade Flow: Domestic Exports
    Classification System: HTS (Harmonized Tariff Schedule) Items
    Years to Report: 1997 - 2018 (Current)
    Countries: Mexico `
 ```
