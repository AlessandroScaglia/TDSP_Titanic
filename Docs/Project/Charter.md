# Project Charter

## Business background

* Who is the client, what business domain the client is in.
* What business problems are we trying to address?

# Client: Titanic Museum

* On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships.
* One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than      * others, such as women, children, and the upper-class.
* Keeping the conditions in mind, we aim to complete the analysis of what sorts of people were likely to survive. In particular we aim   to use tools of machine learning to predict which people were most likely to survive. 

## Scope
* Using data analytics to build a machine learning model to predict the survival of passengers after the sinking of Titanic.

* What data science solutions are we trying to build?
* What will we do?
* How is it going to be consumed by the customer?



## Personnel
* Who are on this project:
	* Company
		* Project lead
		* PM
		* Data scientist(s)
		* Account manager
	* Client
		* Data administrator
		* Business contact
	
## Metrics
* Accuracy - To achieve 100% accuracy by predicting every passenger correctly. We will measure this from the statistical data actually available and compare that to the model results. 

* What are the qualitative objectives? (e.g. reduce user churn)
* What is a quantifiable metric  (e.g. reduce the fraction of users with 4-week inactivity)
* Quantify what improvement in the values of the metrics are useful for the customer scenario (e.g. reduce the  fraction of users with 4-week inactivity by 20%) 
* What is the baseline (current) value of the metric? (e.g. current fraction of users with 4-week inactivity = 60%)
* How will we measure the metric? (e.g. A/B test on a specified subset for a specified period; or comparison of performance after implementation to baseline)



## Plan
* Phases (milestones), timeline, short description of what we'll do in each phase.

## Business Understanding - 09/7/2018 - 13/7/2018 : 5 Working Days 
* Define Business Objectives
* Identify key business variables 
* Define Project Goals 
* Define Project Team 
* Define Success Metrics
* Deliver Charter Document 

## Data Acquisition and Understanding - 13/7/2018 - 17/7/2018 : 3 Working Days 
* Ingest Data 
* Explore the data 
* Deliver Data Quality Report 
* Deliver Solution Architecture 

## Modeling - 16/7/2018 - 19/7/2018 : 3 Working Days 
* Feature Engineering 
* Train Model 
* Evaluate the model
* Define Feature Sets
* Create and Model Report 

## Deployment and Customer Handoff - 20/7/2018 : 1 Working Day
* Deliver final modeling report
* Deliver final solution architecture 
* Project Handoff


## Architecture
* Data
  * What data do we expect? Raw data in the customer data sources (e.g. on-prem files, SQL, on-prem Hadoop etc.)
* Data movement from on-prem to Azure using ADF or other data movement tools (Azcopy, EventHub etc.) to move either
  * all the data, 
  * after some pre-aggregation on-prem,
  * Sampled data enough for modeling 

* What tools and data storage/analytics resources will be used in the solution e.g.,
  * ASA for stream aggregation
  * HDI/Hive/R/Python for feature construction, aggregation and sampling
  * AzureML for modeling and web service operationalization
* How will the score or operationalized web service(s) (RRS and/or BES) be consumed in the business workflow of the customer? If applicable, write down pseudo code for the APIs of the web service calls.
  * How will the customer use the model results to make decisions
  * Data movement pipeline in production
  * Make a 1 slide diagram showing the end to end data flow and decision architecture
    * If there is a substantial change in the customer's business workflow, make a before/after diagram showing the data flow.

## Communication
* How will we keep in touch? Weekly meetings?
* Who are the contact persons on both sides?

* Weekly meetings with the person in contact in the company.
