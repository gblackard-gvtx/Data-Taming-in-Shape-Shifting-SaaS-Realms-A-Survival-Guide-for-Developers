### Titles: 
- Data Taming in Shape-Shifting SaaS Realms: A Survival Guide for Devs

### Category: Community

### Duration: 30 minutes

## Audience:
Python developers that are assuming a role in data engineering for SaaS product or for data engineers building custom tooling and extractions from SaaS product providers.

## Prerequisite knowledge for this session:
Some familiarity with Python, third party libraries like requests and pandas.

## Description 1 :
Many of the products we use today are SaaS based. This has made reporting, analytic and data aggregation more complex then ever. SaaS vendors tend to update APIs with little warning. Microservices have made data extraction daunting. Where do you start? What tools should you use? How do you get started? During this presentation I will discuss starting small, moving fast and about lessons I have learned during my career.

## Description 2 :
You work on a small project or maybe the compony you work for as partnered with a SaaS provider. You are tasked with extracting usage and client data from this system to be used down stream for analytics.
Where do you start? What tools should you use? How do you get started?
During this presentation I will discuss starting small, moving fast and about lessons I have learned during my career.

## Objectives:
Attendees will leave with and better understanding of common issues with SaaS APIs, Tools that can be used implemented quickly to start extracting data, and a better understanding of best practices when working with SaaS API's for data.  
## Detailed Abstract
#### The Problems:
All data is behind and API. The SaaS Provider my provide tooling for data extraction at a extra cost. API could be broken into Microservices requiring you to chain APIs together to get a full picture. SaaS provider are not always the best a communicating what they consider to be small updates.  API versions change as bugs are fixed, these changes my affect later versions. 

#### The Tools:
There are lots of tools that can be used to set up data extraction pipeline. Some of the most popular are:
- Apache Airflows
- Apache NiFI
Under the hood these tools consist of a Web server, a scheduler, a place to store state, a way queue up code, and a way to execute code.
These tools take time to learn and set up. If you are working for a company they may require a lot of red tape.
To move quickly we can create a simpler version of these tools with the following.
- Server
	- Linux or Windows
	- On perm or cloud hosted like and EC2
- Scheduler
	- Chon
	- Windows Task Scheduler
- Tracking State
	- SysLogHandler
	- pywin32
- Execution
	- With both Cron or Windows Task Scheduler we will pass command line arguments to execute the python code.
- 
### Getting Started

