# TricentisOpsInterview
<br/>

# 1. Scenario
You are working with a service provider, which hosting cloud based infrastructure for his customers in MS Azure.  
The most frequent request is to provision virtual machines in bulk for your customers, the VMs you provide are always of the same SKU "Standard_F4s_v2", you always use the default configuration, no spot or low priority instances and also no reserved instances.
As cost is of the highest importance, you need to evaluate the cheapest region available for every customer request.
Your manager asked you to automate the evaluation process of the cheapest region.

## Task
Complete the managers request based on the information provided in scenario one.

## Technical Details

* Pricing API  **https://prices.azure.com/api/retail/prices**
* Script language to use: **PowerShell**

## Scoring criteria
The script will be evaluated based on the following criteria:

* Accuracy of the result
* Code hygiene
<br/>
<br/>

# 2. Scenario
A trainee at your team was given the task to deploy an Azure SQL DB form scratch using an ARM template.
After hours of trial and error the trainee asks you for help with the deployment.

## Task
Look at the src/sqldb-template.json ARM template and make the required changes to make the deployment work.

## Scoring criteria
The template will be evaluated based on the following criteria:

* Accuracy of the result
<br/>
<br/>

# 3. Scenario
One of your companies engineering teams hast started to work on a new cloud based web service and is asking you to help them choose appropriate resources for their new infrastructure.
The team provides you with the following information:
* The service will allow test engineers to share large amounts of test data globally
* The test data should be stored in an SQL DB
* It is very important to provide very fast up and download around the globe
* The service should be deployed via a docker image as the team already has made good experiences with docker
* The infrastructure should be able to scale based on demand and keep idle costs as low as possible 
* The team is also not very experienced when it comes to infrastructure security, so they would appreciate  every security related advise you can give them rated to the new cloud architecture & infrastructure
* (Bonus question: The team has no authentication mechanism for their service, can you suggest one ?)

## Task
Using any tool at your disposal, provide an architecture diagram of a realistic Azure based architecture the team could use for their service.
The infrastructure and services used as part of the architecture should be all Azure native.

## Scoring criteria
The architecture will be evaluated based on the following criteria in the given order:

* Accurate use of Azure based infrastructure
* Scalability
* Security
* Cost
<br/>
<br/>

# Deliver Results
Provide your solutions as a .zip to your contact at Tricentis.
There is no time limit for this exercise but the resolution time will be taken into account.