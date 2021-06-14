---
layout: blogpost
title: "BigQuery in not a Data Strategy - part 1 - Defining Data Strategy"
type: "TECH"
filename: big-query-is-not-a-data-strategy-part2
date: June 30th 2021
image: /images/gena-okami-y1lpMk37EnE-unsplash.jpg
imageAltText: "two cats thick as thieves"
image_attribution: Photo by <a href="https://unsplash.com/@madhatterzone?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Manja Vitolic</a> on <a href="https://unsplash.com/s/photos/nerd-cat?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
---

This is the second in a 4-part series where I talk about what a Data Strategy is, how to identify a lack of or poor data 
strategy in a business and it's systems, how to avoid those problems and what to do if you're already experiencing them 
and how to get out of data choas, into data clarity.

### What is a Data Strategy?

##### What is Data Strategy is Not

I often find it useful to understand what something is in order to better grasp what it is.
Here are some things that a Data Strategy is not:

Having a data dumping ground.
Re-implementing the same transformations all over the organisation's different systems.
Having no idea where the data is used in the business.
There is no strategic plan for data, the business is just dealing with issues and projects as they crop up.
Putting up with painfully slow reports / queries & dashboards.
There is no clear data ownership.
It's difficult to present the data in different formats easily
The business is keeping data to maybe use it one day.

##### Building up a Data Strategy

We want to consider the use of data in an organisation to support 3 main areas:

Business decisions, 
Operational improvements and 
Data that the business generates to sell.

These items tie directly into the Business Strategy, are company wide and require data of appropriate quality and data skills in the business.
What this means it, you need to hire folks who know how to manage data and use it to answer business questions. 
No work being on done on the data or data systems should tie back into the business needs. Often when a data strategy is rolled out
with only engineers involved, it may overly compensate for bad data quality meaning that the infrastructure is over-engineered for 
the businesses needs. If no engineering folks are involved at all, the infrastructure often is woefully under-funded and it 
can become a struggle to perform operations that are required (ie regulartory and complince requirements), 
nevermind those that are innovative. A simple example of a data managment decision gone wrong was a rapid decisions in
the business to move older data into longer term storage on Amazon, without consideration of what was in there or how it might be used.
In the end it cost around £20 000 pounds to query the data for a GDPR request.

So in summary, one wants to consider the following when building a:

How data supports your Business Strategy
Things we **want** to achieve with data (Offensive)
Things we **have** to do with our data (Defensive)

Examples of Offensive things:

* Analytics for Insights
* Data Democratisation
* Multi source Integration
* Data Driven Automation

Examples of Defensive things:

Compliance
* Access Control
* Privacy
* Data Accuracy & Integrity
* Analytics for Protection
* Standardisation
* Governance
* Data Ownership

##### Data Strategy Definition

Given what we know about data strategies now, here is my own attempt at a definition:

A Data Strategy is a vision for how the organisation’s data supports the Business, in offensive and defensive capacities, 
as well as how the data infrastructure and processes need to be managed and which skills are required, to support the Business Strategy.

##### Data Culture

"Culture eats strategy for breakfast".[3]
You can tell people what your strategy is until you're blue in the face, but without imbedding a data culture in your business,
it's unlikely that you'll get the best of your data. We'll discuss some ways to do this in part 4.

References:
[1]
[2]
[3]