---
title: Avoiding Pitfalls in Implementing Data Lakes for Analytics
---

Let's face it: using a data lake to wrangle big data scares us. Too many
people in the C-suite have been burned by can't-miss tech initiatives
before. There's a long list of companies that were sold on the promise
of data warehousing, only to end up pouring money into what became a
dumpster fire that incinerated the careers of many CIOs.

At first glance, data lakes seem to hold the same promise as data
warehouses. The basic premise is the same: collect the data, manipulate
it, and present it for analysis. But as with data warehousing, there are
pitfalls to avoid in implementing a data lake. If you manage to dodge
these traps, you can shepherd your organization through the process of
building a data lake, and coupling it with best-in-breed analytics
tools, and fulfill the promise of using cutting-edge analytics to gain
deeper insights into your business and grow your bottom line.

Avoid Creating Silos
--------------------

Most data lakes are implemented using Hadoop to build data
clusters---which are simply storage spaces for unformatted, large
amounts of structured and unstructured data, in its native format. The
data is formatted on request by data scientists and analysts. This
"schema on read" architecture is less expensive to implement than
traditional "schema on write" architectures which force data to be
cleansed, de-duplicated, and formatted as it goes into the database.

The problem with over-clustering with Hadoop---or similar
technology---is that you can be duplicating data all over the
organization and not know it, thus creating data silos everywhere and
exacerbating problems you may already have with inconsistent information
from your IT systems. This also defeats one key purpose of a data lake,
which is to provide a centralized, flexible data storage facility.

The solution is to constantly monitor the Hadoop clusters you're
creating---especially if you're creating clusters for different
departments or business functions---and keep them to a minimum to avoid
having data duplication and inconsistency issues.

Don't be Rigid with your Data
-----------------------------

The beauty of using a data lake is that data can be formatted when
requested for analysis, depending on who's requesting it, and for what
purpose. This gives companies that implement a data lake very agile,
powerful data analysis capabilities that can be customized to multiple
user constituencies. However, if you build an inflexible architecture
and implement data governance policies that stifle the power of the data
lake, you risk losing the flexibility and power of the data lake.

A scalable technical infrastructure is a must when implementing a data
lake. As data types and volumes change, your architecture must be able
to flex and grow with those changes, otherwise you're just creating
bottlenecks that sap the power of the technology. Also, if you govern
data access too tightly, you inhibit the "freedom of movement and
speech" of data throughout the organization and hinder analytic
breakthroughs and insight generation. Conversely, if you don't monitor
the data and implement some sort of high level governance policies,
you'll end up with garbage piles full of data that no one uses because
its either irrelevant or so dirty that it can't be manipulated.

Do What's Right for the Company
-------------------------------

Everyone (except those curmudgeons who are resistant to change) will be
fairly excited about any new technology that's being implemented. This
is especially true when you tell them that they'll be able to get better
answers to the questions they have and be able to do their jobs more
efficiently and effectively. That's a good thing. However, don't let
excitement and politics rule the data lake implementation process. Do
what's right for the company, not what the most influential
constituencies in the organization demand.

To pick a good pilot or proof-of-concept project, use an
information-gathering process that suits your organization and uncover
the issues that hamper decision-making and business performance. Then,
use the results of that process to understand the needs of different
user groups. This process will help you clearly define the benefits of
the project and uncover the most significant, opportunities and pick the
project that delivers the most value in the shortest time.
