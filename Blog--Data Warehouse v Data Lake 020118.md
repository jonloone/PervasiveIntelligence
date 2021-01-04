---
title: 'It''s not a Fight---You Need both a Data Lake and a Data Warehouse'
---

As I talk to people about their data architectures and data needs, one
question I often get is, "Can I replace my data warehouse (DW) with a
data lake"? Well, in theory, you could, but you really don't want to.
There are differences that make both suitable for different purposes,
but very complementary in your comprehensive data architecture.

I believe the foundation of a data architecture is the [enterprise data
warehouse](https://www.teradata.com/products-and-services/data-warehouse-overview)---or
at a minimum function-oriented DWs that rely on the same governance
structure and data definitions. Traditional DW implementations follow a
set approach: define the requirements, identify (structured) data
sources, define the schema, load and format the data, then distribute
the data through presentation layers.

That works well as long as the data fits what you've defined. You can
use historical transaction or event data in your DW to figure out what
happened and why it might have happened. Based on available data, you
can form hypotheses and test them against the data in the warehouse to
either confirm or refute your suspicions.

The DW is your go to, your standby, your Old Faithful. It's the backbone
of your daily business---how you keep your hand on the pulse of what's
happening. It has structured, processed, clean data that can be accessed
almost immediately, and---when coupled with best-of-breed BI tools---it
can democratize BI and put the power of analysis in the hands of even
less-than-tech-savvy users. Also, because it's governed and contains
high-quality data, the answers it provides present a single version of
the "truth" no matter who's asking.

Changes in Data Dictate Changes in Technology
---------------------------------------------

Data warehouses have their strong points, but no one needs to tell you
that the nature of data has changed significantly over the past decade.
The volume of unstructured and streaming data has far surpassed that of
traditional, structured data. That flood has given rise to a new
repository: [the data lake](https://www.thinkbiganalytics.com/kylo/).
Data lakes store unstructured data and format it when it's queried to
enable broader and deeper data exploration by data scientists.

Data lakes ingest raw data---either in batches or in real time---and
store it in its native format. The data is curated by capturing
metadata, but it's only formatted on read---i.e., when someone wants to
retrieve the data. Because much of the technology is open source and the
processing at load time is less, they're also cost-effective.

Data lakes also enable a different analytical process. Instead of
forming a hypothesis and testing it against the data, you build analysis
"sandboxes" where data scientists can use sophisticated modeling
techniques to parse the data to spot trends and patterns. In essence,
the data scientist uses a model to make an observation or spot a
pattern, then forms a hypothesis. It's kind of backwards to the EDW
analysis approach, but it's complementary.

The data lake is the hot new toy that you can't wait to get your hands
on, just to see how many new and nifty things you can do with it. Data
storage is also relatively less expensive, and the data lake can be
reconfigured when you want. It's great for data exploration and
discovery, which will enable you to generate all sorts of new insights
that were previously unavailable with EDWs.

However, data quality is often spotty (which can be remedied with good
data governance) and---here's the big rub---it's slow in returning
answers to queries because of the transformation that must take place
before the results are returned. So, there's your answer as to why you
just can't throw everything into the data lake---it's slow, can be of
specious quality, and it's meant for exploration and discovery, not
mundane business analysis.

The Answer is in the Purpose
----------------------------

In the end, it's not an either-or thing; it's a both thing. Look at it
this way: it depends on how you want to use it. If your purpose is
providing data to dashboards and self-service analytics/BI, and you need
fast, repeatable results, then your DW is indispensable. If you're
interested in exploring the vast new world of unstructured data and
finding trends and patterns in your data that will give you deeper
insights into what might happen, then the data lake is the way to go. Of
course, you're interested in doing both, so you need both.
