# The Microsoft Technology Center "Data Literacy" Series 

>"We have a data lake, a data warehouse, and Power BI...but no one has still been able to show us how to leverage our data assets to provide actionable intelligence."  -- _heard during a recent MTC engagement_
## Moving Towards an ETL-Free World

Dave Wentzel
[LinkedIn Profile](https://linkedin.com/in/dwentzel)  
Philadelphia Microsoft Technology Center  
Monday, March 14, 1-3 pm EST


Data warehouses (EDWs/DWHs) have their use cases, but they might be stifling your analytics innovations in 2022.  

So is ETL.  

So is your Data Lake!!

In this session we’ll walk through why the warehouse might not be the best place for your analytics data.  We’ll show you a much simpler alternative that is easier for most Citizen Analysts to understand and will help you on your Self-Service Analytics journey.  Even if you are satisfied with your data warehouse investment, we’ll show you some complementary approaches that may improve your analytics time-to-value.  Finally, we’ll show you some Azure tools and patterns that will increase your data team’s productivity almost immediately.  

[Slides](./EDWs.pdf)

### Demos/Code

* [Using CETAS as a replacement for ETL](https://github.com/davew-msft/synapse)
  * I have lots of demos and sample code available in this repo


### How to Make the Journey Towards an ETL Free World

* embrace data literacy/self-service analytics
* try to get the Citizen Analyst a _modicum_ of SQL literacy
* **late** data governance
  * an open culture
* decentralized analytics culture (CoE Model)
* think creatively about how you deploy analytics
  * corporate data lakes vs departmental data lakes
  * the data ocean
* think about data sharing (data mesh/data fabric/data marketplaces/data virtualization)
* think about 3rd party data sharing
  * how can you share your data securely?
    * the "data clean room"
    * PII/PHI/sensitive data
* think it terms of streams of data

### Questions?

* Isn't this what API's were supposed to solve?
* ETL seems to take longer when an analyst does it vs a Data Engineer.  Why?  Doesn't this mean this method doesn't work?  
  * How do we measure effectiveness?
* How does this work for _data monetization_ scenarios?  