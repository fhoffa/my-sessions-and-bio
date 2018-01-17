# my-sessions-and-bio
My bio and the list of session agendas

## Bio

Felipe Hoffa

Developer Advocate @Google. From Chile to San Francisco to the world.

In 2011 Felipe Hoffa moved from Chile to San Francisco to join Google as a Software Engineer. Since 2013 he's been a Developer Advocate on big data - to inspire developers around the world to leverage the Google Cloud Platform tools to analyze and understand their data in ways they could never before. You can find him in several YouTube videos, blog posts, and conferences around the world.

Follow Felipe at [@felipehoffa](https://twitter.com/felipehoffa).

## Links

- https://twitter.com/felipehoffa
- https://medium.com/@hoffa
- https://www.youtube.com/watch?v=-VLlMl5zK3k&list=PLG1fouPFF9lwF7l0tg81qUoJk4n3H5w5y


## Selected writings

- [Counting uniques faster in BigQuery with HyperLogLog++](https://cloud.google.com/blog/big-data/2017/07/counting-uniques-faster-in-bigquery-with-hyperloglog)
- [Who contributed the most to open source in 2017? Let’s analyze GitHub’s data and find out](https://medium.freecodecamp.org/the-top-contributors-to-github-2017-be98ab854e87)
- [The most famous reddit accounts](https://medium.com/@hoffa/the-most-famous-reddit-accounts-c9958b5bc376)
- [Leading with commas — ugly or efficient? An investigation over 320 GB of SQL code](https://hackernoon.com/winning-arguments-with-data-leading-with-commas-in-sql-672b3b81eac9)
- [A Google SRE explores GitHub reliability with BigQuery](https://medium.com/google-cloud/sla-slo-explored-with-github-and-bigquery-e6a135919a8e) (SLAs and SLOs with real data)

## Videos

- [SQL: Where should the commas go](https://www.youtube.com/watch?v=ppioMSOi2Ho) (5:39)
- [Playlist](https://www.youtube.com/watch?v=ppioMSOi2Ho&list=PLG1fouPFF9lwF7l0tg81qUoJk4n3H5w5y)

## Sessions

### What can we learn from 1.1 billion GitHub events and 42 TB of code?

Anyone can easily analyze the more than five years of GitHub metadata and 42+ terabytes of open source code. We’ll leverage this data to understand the community and code related to any language or project. Relevant for open source creators, users, and choosers.

#### Description

“Data gives us insights into how people build software, and the activities of open source communities on GitHub represent one of the richest datasets ever created of people working together at scale.” —GitHub Universe 2016

With Google BigQuery anyone can easily analyze the more than five years of GitHub metadata and 42+ terabytes of open source code. Felipe Hoffa explains how to leverage this data to understand the community and code related to any language or project. Relevant for open source creators, users, and choosers, this is data that you can leverage to make better choices.

Topics include:

- How it’s run
- How coding patterns have changed through time
- Guiding your project design decisions based on actual usage of your APIs
- How to request features based on data
- The most effective phrasing to request changes
- Effects of social media on a project’s popularity
- Who starred your project and what other projects interest them
- Measuring community health
- Running static code analysis at scale
- Tabs or spaces? Where should commas go?
- Digging deeper into all the Python code.


### Exploring big data on the cloud

What we know, what is happening, and what we are made of: Open Data, BigQuery, SQL

We'll talk and demo the tools and methodologies - that you can use - to understand the world and what we are made of. Interactively leveraging tools like Google BigQuery we'll discover knowledge on 3 immense datasets: Wikipedia, GDELT, and the personal genome.

### Advanced BigQuery and internals

Covering the latest advancements and BigQuery internals.

### GDELT + BigQuery: Understanding global society through SQL

In this session:

- Learn what GDELT is – an open dataset of the last 36 years of worldwide events and narratives, updated in real time and live-translated from 65 languages
- Learn how to access GDELT, with live queries exploring the past, present, and possible future of the worldwide news

Put simply, the GDELT Project is a real-time open data global graph over human society as seen through the eyes of the world’s news media, reaching deeply into local events, reaction, discourse, and emotions of the most remote corners of the world in near-real time, and making all of this available as an open data firehose to enable research over human society.

This talk will explore both the technical underpinnings and workflows of the GDELT Project, and how Google BigQuery is enabling GDELT to explore real-time whole-of-data exploration of the underlying patterns of global human society through the eyes of the world’s news media.

With Kalev Leetaru, the founder of the GDELT Project, covers the first half of the presentation discussing everything from the technical to the methodological to the sociological issues in building one of the world’s largest open data platforms on human society. Felipe Hoffa, developer advocate for Google BigQuery, takes the second half of the presentation to walk through a number of case examples of how BigQuery is enabling real-time whole-of-data access to GDELT that enables the kind of speed-of-thought exploration simply not possible in previous architectures.

### Apache BEAM + Google Dataflow: The new open model for batch and stream processing

In 2004 Google published the MapReduce paper, a programming model that kick-started big data as we know it. Ten years later, Google introduced Dataflow - a new paradigm for big data, integrating batch and stream processing in one common abstraction. This time the offer was more than a paper, but also an open source Java SDK and a cloud managed service to run it. In 2016 big data players like Cask, Cloudera, Data Artisans, PayPal, Slack, Talend joined Google to propose Dataflow for incubation at the Apache Software Foundation - now accepted as Apache Beam. Dataflow is here, not only unifying batch and streaming, but also the big data world.

In this talk we are going to review Dataflow's differentiating elements and why they matter.  We’ll demonstrate Dataflow’s capabilities through a real-time demo with practical insights on how to manage and visualize streaming data flows.


## Forked sessions: Sessions I'm happy to deliver and go deeper, based on my teammates original presentations

### BigQuery and TensorFlow: How a data warehouse + machine learning enables "smart" queries

* BigQuery and TensorFlow: How a data warehouse + machine learning enables "smart" queries

BigQuery is Google’s fully managed, petabyte-scale, low-cost enterprise data warehouse. By leveraging the petabit network and tens of thousands of servers in Google’s data center, BigQuery allows you to execute your SQL as a massively parallel processing query with hundreds of CPU cores and ample disk storage, scanning and aggregating terabytes of data in seconds.

BigQuery also features an unique technology, user-defined functions (UDF), that let you define your own SQL function with JavaScript code, embedded in SQL. UDF is the key to integrating the scalable data warehouse with the power of machine learning, using TensorFlow and ML Engine and enables a variety of “smart” queries, such as similarity searches and recommendations on images, documents, products, or users. You can even run neural network predictions inside BigQuery.

In this session we'll demonstrate how to integrate UDF with BigQuery, TensorFlow, and ML Engine and build a powerful solution with cloud data warehouses and machine learning.

-- Forked from [Kaz Sato's](https://www.youtube.com/watch?v=Ov3Om5Y_Fbg).

### Introduction to Big Data - tools that deliver deep insights

In this session, we'll explain some big data basics and provide a high-level introduction to Google Cloud's big data tools, including Google BigQuery, Cloud Dataproc, Cloud Dataprep, Cloud Datalab, Cloud PubSub and Cloud Dataflow. You'll learn how to harness the power of big data with these tools, so that you can turn data insights into strategies for your own organisation.

-- Forked from [William Vambenepe's](https://www.youtube.com/watch?v=dlrP2HJMlZg).

### Coping with IOT data on GCP

One of the most exciting things about the Internet of Things is how much data it generates. This huge sea of data is what allows us to use machine learning and other emerging technologies to give our users useful insights into their lives. Unfortunately, the technologies and protocols we developed to scale the web aren’t a perfect fit. They don’t always scale in the right way. We need a new set of tools to make our projects successful. In this talk Felipe Hoffa, a Developer Advocate at Google, will share a recipe for dealing with high volume IoT data: Google Cloud Pub/Sub, Dataflow, and BigQuery. This talk will include demos, and a discussion of managed and open source options.

- Forked from [Jen Tong's](https://www.youtube.com/watch?v=-6NInkg3dYk).

### Beyond Firebase Analytics - Unleashing BigQuery's Raw Power 

Are you ready to link your Firebase Analytics with Google BigQuery? In this session, we are going to explore the what, why and hows. First, we are going to learn what is BigQuery and what are its unique advantages. Understanding BigQuery will lead us to see why it's a good idea to get our daily dumps of raw Firebase Analytics data into it - and how. Finally, we are going to delve into data exploration, learning how to play with the Firebase exports in BigQuery and join these tables with other datasets for fun, exploration, and visualization.


