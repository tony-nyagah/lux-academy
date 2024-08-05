# Data Engineering: A Beginner's Guide to Concepts, Tools, and Responsibilities

## Table of Contents

1. [Introduction](#introduction)
   - [Personal background](#personal-background)
   - [Motivation for exploring data engineering](#motivation-for-exploring-data-engineering)

2. [What is Data Engineering?](#what-is-data-engineering)
   - [Definition and core concepts](#definition-and-core-concepts)
   - [The role of data engineering in the data ecosystem](#the-role-of-data-engineering-in-the-data-ecosystem)
   - [How it differs from data science and software engineering](#how-it-differs-from-data-science-and-software-engineering)

3. [Key Concepts in Data Engineering](#key-concepts-in-data-engineering)
   - [Data pipelines](#data-pipelines)
   - [ETL (Extract, Transform, Load) processes](#etl-extract-transform-load-processes)
   - [Data modeling](#data-modeling)

4. [Essential Tools for Data Engineers](#essential-tools-for-data-engineers)
   - [Programming languages](#programming-languages)
   - [Big data processing frameworks](#big-data-processing-frameworks)
   - [Workflow management tools](#workflow-management-tools)
   - [Data warehousing solutions](#data-warehousing-solutions)
   - [Version control and collaboration tools](#version-control-and-collaboration-tools)

5. [Responsibilities of a Data Engineer](#responsibilities-of-a-data-engineer)

6. [Getting Started in Data Engineering](#getting-started-in-data-engineering)
   - [Recommended learning resources](#recommended-learning-resources)
   - [Projects to build your portfolio](#projects-to-build-your-portfolio)
   - [Transitioning from backend development to data engineering](#transitioning-from-backend-development-to-data-engineering)

7. [Conclusion](#conclusion)
   - [Recap of key points](#recap-of-key-points)
   - [Future outlook for data engineering](#future-outlook-for-data-engineering)
   - [Encouragement for readers to explore the field](#encouragement-for-readers-to-explore-the-field)


## Introduction
### Personal background
I have been a backend developer for about 4 years now and am only recently realizing I might be good at it 🤓. Solving problems using code can be very fun when things go right.
### Motivation for exploring data engineering   
The decision to go with this path has come about because I realized my current backend development work intersects quite nicely with the field of data engineering. They both essentially deal with moving data around.

## What is Data Engineering?
### Definition and core concepts
> Data engineering refers to the building of systems to enable the collection and usage of data. This data is usually used to enable subsequent analysis and data science; which often involves machine learning.Making the data usable usually involves substantial compute and storage, as well as data processing. - [Wikipedia](https://en.wikipedia.org/wiki/Data_engineering)

To sum it up in very simple terms, data engineering involves the building of systems to enable the collection and storage of data for later use.

### How it differs from data science and software engineering
While data engineering involves collecting and storing data, data science involves analyizng said data to find patterns and insights.

Software engineering on the other hand involves designing and developing software applications. The applications may range from simple web pages to complex ecommerce systems.

## Key Concepts in Data Engineering
Some of the key concepts you need to understand about data engineering include:
### Data pipelines
> A data pipeline is a method in which raw data is ingested from various data sources, transformed and then ported to a data store, such as a data lake or data warehouse, for analysis. - [IBM](https://www.ibm.com/topics/data-pipeline)

A data pipeline is essentially the steps of ingesting, transforming and storing data in a [data warehouse](https://cloud.google.com/learn/what-is-a-data-warehouse) or [data lake](https://cloud.google.com/learn/what-is-a-data-lake).    
A properly structures data pipeline should make the process of getting and storing data easier and more efficient.

### ETL (Extract, Transform, Load) processes
As the names suggest, the processes involve extracting data from a data source i.e. through web scraping, transforming the data to fit our needs i.e. removing unneccesary data or converting it to fit our needs and then loading it into our database, data warehouse or data lake.

### Data warehousing
> A data warehouse is a large central storage unit for current and historical data collected from various sources. Unlike databases used for daily operations, data warehouses hold historical information, often from multiple departments or even companies. This allows data analysts to examine trends over time, identify patterns, and gain insights that can inform better business decisions. - [Coursera](https://www.coursera.org/articles/data-warehouse) 

A data warehouse is mainly used to keep huge amounts of data in a central place. This data can be used to analyze trends and generate business insights. This can be greatly useful for planning where a business will go next.

### Data Modeling
> Data modeling is the process of creating a visual representation or a blueprint that defines the information collection and management systems of any organization. - [Amazon](https://aws.amazon.com/what-is/data-modeling/)

This basically helps different stakeholders to have a unified view of the organization's data, the model outlines what data is collected, the methods used to store the data and how the data is to be analyzed. Creating a data model should be one of the first things you do before engaging in a data engineering project.

## Essential Tools for Data Engineers
### Programming languages
Data engineers use many programming languages such as Python, Java, C#, C++, Go, etc. As of now, Python is dominant language in the field but languages such as R and Scala are valuable tools.    
Having a basic understanding of programming concepts will help you build up your skills in data engineering.

### Big data processing frameworks
Big data processing frameworks such as Apache Spark, Apache Flink, etc. are used to process large amounts of data in real time. These tools are all made specifically for handling the huge amounts of data we see in the world right now.

### Workflow management tools
Tasks such as data scraping can prove tedious if done manually. This is where workflow management tools come in. These tools can be used to automate repetitive tasks in the data engineering process.    
one tool that I am very interested in starting to use is [Apache Airflow](https://airflow.apache.org). I recently tried it on a sample project and loved that I could actually see what tasks i had setup in my browser.

### Version control and collaboration tools
Version control and collaboration tools can help you to keep track of your work. They can also help you to collaborate with others.    
Central to this is [Git](https://git-scm.com/). It is a [version control system](https://en.wikipedia.org/wiki/Version_control) that allows you to track changes in your work and pretty much the standard. Using this in collaboration with sites like [GitHub](https://github.com/) to allow others access your code over the internet is a must.

## Responsibilities of a Data Engineer
Some of the responsibilities if a data enginerr include:
**1. Designing and maintaining data architecture** - This includes creating data models and ensuring that dtaa is stored in the right/agreed upon format.
**2. Building and optimizing data pipelines** - To maintain sanity, a data engineer should build and optimize data pipelines that ensure data quality and integrity.
**3. Collaborating with data scientists and analysts** - The data acquired and stored by the engineer has to be used somewhere and this is where the data analysts and data scientists come in. They help generate insights and predictive capabilities respectively using the acquired data.

## Getting Started in Data Engineering
### Recommended learning resources
There's no better way to get started in any sort of tech learning adventure than engaging in a community. A community such as [Lux Tech Academy](https://ke.linkedin.com/company/lux-tech-academy) is a great place to start. This is where my intro to data engineering came from.
Some other great resources include:
* FreeCodeCamp (they have a course for everything): [Data Engineering For Beginners](https://www.youtube.com/watch?v=PHsC_t0j1dU)

### Transitioning from backend development to data engineering
This is specifically for those who have some experience with the backend and now want to focus on data. The transition won't be that hard but it requires a lot of effort and patience on your part. If you know Python and SQl you're over 50% ready 😄

## Conclusion
### Future outlook for data engineering
The field of data: data analytics, data science and data engineering, is evolving every single day what with the development of [Large Language Models (LLMs)](https://en.wikipedia.org/wiki/Large_language_model) and the ongoing endavour to create [Artificial General Intelligence (AGI)](https://en.wikipedia.org/wiki/Artificial_general_intelligence).   
I believe the future in anything data focused is bright. Dipping your toes in the field will give you a major boon in the long run.

### Encouragement for readers to explore the field
My interest in data was sparked after seeing some good looking charts on a report. This might be a dumb reason to get into this field but it made me realize how much data is out there just waiting to be gathered and harnessed into beautiful insights.   
I hope that if you've gotten this far you have a better understanding of data engineering and might even taken an interest in the field.   
Thank you for reading.



