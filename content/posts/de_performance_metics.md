+++ 
draft = true
date = 2024-02-21T21:40:50-05:00
title = "Measuring Data Teams"
+++

I'm not a huge fan of measuring individual performance based on metrics, many of them are easy to game and not very informative as to actual performance. Think the dreaded lines of code, commit counts, etc. However metrics are a great way to get insight into the performance of teams, systems, and organizations. Data work, like software engineering, is a team sport that requires a number of players to come together to ensure success. Curious, though data engineering teams spend a lot of time prepping data for business metrics, they frequently do not track metrics for their own performance. 

Where to start? Having managed both engineering and data teams for a few years I've come to rely on a few different measures to help me understand team health and performance. We all stand on the shoulders of others, so here I borrow some trusted metrics commonly used when evaluating engineering teams and apply them to the specifics of data engineering. These are adapted from the [DORA](https://dora.dev) and [SPACE](https://queue.acm.org/detail.cfm?id=3454124) metrics. 

# Lead Time

What it measures: How much time is between the beginning of a project’s development and its delivery to the stakeholder. This could be anything from a new data product, data mart, or even an dashboard.

Measurement: Lead time in days

Impact: Increased planning accuracy and business agility

# Lead Time for Changes

What it measures: How much time it takes committed work to get into production

Measurement: Lead time in days

Impact potential: Developer efficiency and business agility

# Pipeline Deployment Frequency

What it measures: How often pipelines successfully push data to production.

Measurement: Deployments per day

Impact potential: Increased data freshness for better decisions

# Change Failure Rate

What it measures: The percentage of deployments leading to a degradation in service that must be addressed

Measurement: Number of incidents divided by number of deployments

Impact potential: Increase stakeholder satisfaction by decreased number of outages

# Time to Restore

What it measures: How long it takes an organization to recover from a failure in production

Measurement: Restore Time in hours

# Cycle Time

What it measures: How much time do individual project stages take

Measurement: Cycle time in days

Impact potential: Ability to forecast delivery

# Work-in-progress 

What it measures: The state of the work in progress

Measurement: Number of tasks in progress

Impact potential: Identify bottlenecks and sunk costs

