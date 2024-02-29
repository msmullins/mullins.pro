+++ 
draft = true
date = 2024-02-21T21:40:50-05:00
title = "Measuring Data Teams"
+++

I'm not a huge fan of measuring individual performance based on metrics, but metrics can be a great way to get insight into the performance of teams and systems. Data engineering teams spend a lot of time prepping data for business metrics but frequently don't track metrics for their own performance. Here I borrow some trusted metrics commonly used when evaluating engineering teams and apply them to the specifics of data engineering. These are adapted from the [DORA](https://dora.dev) and SPACE metrics. 

# Lead time

What it measures: How much time is between the beginning of a project’s development and its delivery to the stakeholder. This could be anything from a new data product to data mart. A defense contractor once told me their mean lead time was 16 weeks! Do better.

Measurement: Lead time in days

Impact: Increased planning accuracy and business agility

# Lead time for changes

What it measures: How much time it takes a commit to get into production

Measurement: Lead time in days

Impact potential: Developer efficiency and business agility

# Pipeline deployment frequency

What it measures: How often pipelines successfully push to production.

Measurement: Deployments per day

Impact potential: Increased data freshness

#. Cycle time

What it measures: How much time do individual project stages take

Measurement: Cycle time in days

Impact potential: Ability to forecast delivery

# Work-in-progress 

What it measures: The the state of the work in progress

Measurement: Number of tasks in progress

Impact potential: Identify bottlenecks and sunk costs

# Change failure rate 

What it measures: The percentage of deployments leading to a degradation in service that must be addressed

Measurement: Number of incidents divided by number of deployments

Impact potential: Increase customer satisfaction by decreased number of outages

# Time to restore service 

What it measures: How long it takes an organization to recover from a failure in production

Measurement: Restore Time in hours


