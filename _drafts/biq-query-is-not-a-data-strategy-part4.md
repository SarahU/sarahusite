---
layout: blogpost
title: "BigQuery in not a Data Strategy - part 4 - Data Chaos to Data Clarity"
type: "TECH"
filename: big-query-is-not-a-data-strategy-part4
date: June 30th 2021
image: /images/gena-okami-y1lpMk37EnE-unsplash.jpg
imageAltText: "two cats thick as thieves"
image_attribution: Photo by <a href="https://unsplash.com/@madhatterzone?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Manja Vitolic</a> on <a href="https://unsplash.com/s/photos/nerd-cat?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
---

This is the fourth in a 4-part series where I talk about what a Data Strategy is, how to identify a lack of or poor data 
strategy in a business and it's systems, how to avoid those problems and what to do if you're already experiencing them 
and how to get out of data chaos, into data clarity.

### Moving out of Data Chaos?

It's useful to know how to avoid mistakes (not that you shouldn't try things. There's a lot going on in the data world, 
but we hope to avoid costly errors), but what if you already have systems in place, and you're experiencing a large number
of the symptoms we discussed in part 1?

Well, starting with what not to do: we don't panic and we don't stop building. It can be tempting to put off data related
work while waiting for a data platform to be built or improved upon but this work takes time and if the business requires 
some functionality based on data that is build-able now, albeit in a quick and dirty way, simply continue and prove the
worth of that product and let the data platform improvement work replace it later. Technology improvement is always present
in the strategy of a successful business and replacing tech over time is not unusual for products. It is the same for data systems.

##### First steps

Here are some items to cover off as you start your data journey:

####### Add timestamps and other audit & lineage metadata
This metadata will be useful later for Data Lineage. It's also useful for audits, especially if the data is version,
it can helped to know who changed what to when. You can also keep track of these changes in a separate system using
events (ie sending audit events to another data stream/system), but I would also keep the time on the original record for redundancy.

####### Understand your org's data flow
Getting insight into how data is being used in the organisation can be insightful. It might also bring up a few surprises so
be prepared for that! There are ways to automate this but I would encourage you to make this a manual journey of discovery
and really talk to the folks using the data and understand the why's, how's and struggles of their usage. This way you involve others
on the data journey and those relationships will stengthen the data culture.

####### Find data owners

####### Mitigate access with current controls you
####### Start a Data Dictionary
####### Start storing important Raw data
####### Data Guild / CDO / Champions / Dept.

##### Focus on these next:
Scientists, Analysts: >=50% time on cleaning, data pipelines hire Engineers
Plan data migration & pipeline work ensure one way data flows , into the necessary formats for the tools that use them
Get rid of data not in use , unless legally required to keep it (can it be aggregated?)
Focus on your most valuable data first
Work towards Data Maturity

##### Data Culture

"Culture eats strategy for breakfast".[3]
You can tell people what your strategy is until you're blue in the face, but without imbedding a data culture in your business,
it's unlikely that you'll get the best of your data. We'll discuss some ways to do this in part 4.

References:
[1]
[2]
[3]