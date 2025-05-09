# Task One: Data Preparation and Customer Analytics

Conduct analysis on your client's transaction dataset and identify customer purchasing behaviours to generate insights and provide commercial recommendations.

**What you'll learn**
- Understand how to examine and clean transaction and customer data.
- Learn to identify customer segments based on purchasing behavior.
- Gain experience in creating charts and graphs to present data insights
- Learn how to derive commercial recommendations from data analysis.

**What you'll do**
- Analyze transaction and customer data to identify trends and inconsistencies. 
- Develop metrics and examine sales drivers to gain insights into overall sales performance. 
- Create visualizations and prepare findings to formulate a clear recommendation for the client's strategy.

## Background Information

You are part of Quantium’s retail analytics team and have been approached by your client, the Category Manager for Chips, who wants to better understand the types of customers who purchase Chips and their purchasing behaviour within the region.

The insights from your analysis will feed into the supermarket’s strategic plan for the chip category in the next half year.

You have received the following email from your manager, Zilinka.

*Hi,*

*Welcome again to the team, we love having new graduates join us!* 

*I just wanted to send a quick follow up from our conversation earlier with a few pointers around the key areas of this task to make sure we set you up for success.*

*Below I have outlined your main tasks along with what we should be looking for in the data for each.*

*Examine transaction data – look for inconsistencies, missing data across the data set, outliers, correctly identified category items, numeric data across all tables. If you determine any anomalies make the necessary changes in the dataset and save it. Having clean data will help when it comes to your analysis.*

*Examine customer data – check for similar issues in the customer data, look for nulls and when you are happy merge the transaction and customer data together so it’s ready for the analysis ensuring you save your files along the way.*

*Data analysis and customer segments – in your analysis make sure you define the metrics – look at total sales, drivers of sales, where the highest sales are coming from etc. Explore the data, create charts and graphs as well as noting any interesting trends and/or insights you find. These will all form part of our report to Julia.*

*Deep dive into customer segments – define your recommendation from your insights, determine which segments we should be targeting, if packet sizes are relative and form an overall conclusion based on your analysis.*

*Make sure you save your analysis in the CSV files and your visualisations – we will need them for our report. If you could work on this analysis and send me your initial findings by end of next week that would be great.*

*Looking forward to reviewing your work.*

*Thanks,*

*Zilinka*

## Here is your task

We need to present a strategic recommendation to Julia that is supported by data which she can then use for the upcoming category review. However, to do so, we need to analyse the data to understand the current purchasing trends and behaviours. The client is particularly interested in customer segments and their chip purchasing behaviour. Consider what metrics would help describe the customers’ purchasing behaviour.  

We have chosen to complete this task in R, however you will also find Python to be a useful tool in this piece of analytics. If you aren’t familiar with R or Python we would recommend searching a few online courses to help get you started. We have also provided an R solution template if you want some assistance in getting through this Task. Whilst its possible to complete the task in Excel you may find the size of the data and the nature of the tasks is such that it is more difficult to complete in Excel.  

To get started, download the resource csv data files below and begin performing high-level data checks such as:

- Creating and interpreting high-level summaries of the data
- Finding outliers and removing these (if applicable)
- Checking data formats and correcting (if applicable)

You will also want to derive extra features such as pack size and brand name from the data and define metrics of interest to enable you to draw insights on who spends on chips and what drives spends for each customer segment. Remember, our end goal is to form a strategy based on the findings to provide a clear recommendation to Julia the Category Manager so make sure your insights can have a commercial application.

As we are in the early stages of this analysis Zilinka has asked us to submit our initial findings, so please save your code as a .pdf file and upload it to unlock the model answer.

Note: that this is an open-ended case study that can be approached in many ways. Example answer is in R.

## Here are some resources to help you

- [QVI Transaction Data](https://github.com/woaine/quantium-data-analytics/blob/020eb1c29fdc8d037d780562f8fedc73c142468a/data/raw/QVI_transaction_data.xlsx)
- [QVI Purchase Behaviour](https://github.com/woaine/quantium-data-analytics/blob/020eb1c29fdc8d037d780562f8fedc73c142468a/data/raw/QVI_purchase_behaviour.csv)
- [R Solution Template](https://github.com/woaine/quantium-data-analytics/blob/1c23741c2738e038053b563e71292bf14588a15a/data/raw/InsideSherpa_Task1_DraftSolutions%20-%20Template.pdf)

`LIFESTAGE`: Customer attribute that identifies whether a customer has a family or not and what point in life they are at e.g. are their children in pre-school/primary/secondary school.

`PREMIUM_CUSTOMER`: Customer segmentation used to differentiate shoppers by the price point of products they buy and the types of products they buy. It is used to identify whether customers may spend more for quality or brand or whether they will purchase the cheapest options.

Pro analytics Tip: While the data set would not normally be considered large some operations may still take some time to run. 

This is normal and to be expected when dealing with data sets at Quantium. Whilst your analysis is based on the whole data set you may want to try some strategies to try running sample solutions on a smaller subset of data I.e. create a sample solution using some of the data while it uploads.