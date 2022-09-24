# Week: APIs
<hr>

![Map Image](images/img_iphs290_api_alvensia-angela-_N0srPVrfVk-unsplash.jpg)

## Overview

Data is the Alpha and Omega of Data Science, Machine Learning and Deep Learning. The creativity, expressiveness and strength of your analysis will be bounded by the data you have. The quality of your dataset can be measured along many dimensions including the type/number of features, originality, number of datapoints, accuracy, coherence, etc.

While there are a rapidly growing number of public datasets, they often are best used for tutorials, training and establishing baseline metrics. It is extremely difficult to create new, innovative and meaningful data analysis based upon datasets already mined by others. This week we study Web Scraping and APIs so you will be able to create your own unique datasets based upon the wide variety and vast quantity of information available on the Web. 

Data constantly flows constantly in networks under **two basic paradigms**. First, Information intended for humans exit computer networks via a interactive and/or visual interfaces. These include (a) a widows-based ***Graphical User Interfaces (GUIs)*** like those in MacOS and WindowsOS, and (b) a text-based *interactive REPL command line shell* (read-execute-print-loop) .

***Machine-to-Human GUIs*** are carefully designed to represent, architect, and sequence information to leverage human intuitions and cognitive processes. Unfortunately, programmatically scraping data from web GUIs can be slow, error-prone, fragile and (in many cases) impossible due to the limited resources, continual design updates, technical anti-scraping barriers and legal concerns. Web scraping can be viable for creating unique datasets based upon simpler open web sites or for harvesting smaller high-value data. 

To web scrape effectively, you will need to learn several core concepts. Content (HTML) and presentation (CSS) metatags organize data within a web page. Specific data within a web page can be uniquely identified and extracted using XPath notation and Beautiful Soup 4. Web frameworks and designs change frequently, are often deeply nested in human-unfriendly fashion and follow no universal pattern which makes web scraping a constant challenge.

Secondly, ***machine-to-machine API communications*** at the application layer are governed by strictly defined protocols like REST and GraphQL and exchange data in well-structured file formats like JSON and XML. Machine-to-machine communications have the advantages of speed, scalability and programmable automation. Many websites make their data available via open and/or paid access using their own API. In stark contrast to web pages, APIs and data exchange formats are (mostly) precisely defined by specificiations created by centralized standards committees. These standards rarely change and share universal best practices which makes exchanging data or creating unique datasets via APIs fast, efficient and reliable.

This week introduces common web scraping tools and programming practices. It is particularly useful to learn this in a collaborative lab environment since there are so many rules and exceptions to the rule it can be hard to quickly get a functional overview. We’ll also practice automating calls to popular REST API services to compile unique datasets. This includes learning the API for Twitter, Reddit and Instagram as well as the libraries to convert between JSON datafiles and internal Python data types like dicts{} and Pandas DataFrames.



## Applications

Make sure you completed last week's DataCamp:
- [Intermediate Importing Data in Python (2hrs) Chp 1-4](https://app.datacamp.com/learn/courses/intermediate-importing-data-in-python)

- [Monday]: 
    * (last Friday's Video)[BA 322 | Scrape Zappos with Chrome Extension: Free Web Scraper (27:50)](https://www.youtube.com/watch?v=BRyfnI6Jtzs)
    * Find Website and Scrape with Chrome Plugin, esp with Geolocation data (e.g. [MarineTraffic.com](https://www.marinetraffic.com/) ) and scrape with Chrome Extension
    * [Visual Studio Code 2022 (19:36)](https://www.youtube.com/watch?v=fJEbVCrEMSE&t=913s)
    * [Virtual Environments in Python - Crash Course (13:32)](https://www.youtube.com/watch?v=IAvAlS0CuxI&t=460s)
    * Presentation
    * Bring Website to Scrape, with Geo Longitude/Latitude if possible.

- [Wednesday]:
    * [Step-by-Step Guide to Making Your First Request to the New Twitter API](https://developer.twitter.com/en/docs/tutorials/step-by-step-guide-to-making-your-first-request-to-the-twitter-api-v2))
    * [Twitter API with Python (Complete Guide)](https://www.jcchouinard.com/twitter-api/)
    * [GitHub Tutorial - Beginner's Training Guide (8:11)](https://www.youtube.com/watch?v=iv8rSLsi1xo)
    * [Git - The Simple Guide](http://up1.github.io/git-guide/index.html)


- [Friday]: 
    * (From Last Week) [Automated Twitter Bot in Python (19:02)](https://www.youtube.com/watch?v=UGv_bJkF1kg)
    * [How to use JSON in Python (6:10)](https://www.youtube.com/watch?v=-51jxlQaxyA&t=2s)
    * [Python MySQL Tutorial - Setup & Basics (13:09)](https://www.youtube.com/watch?v=3vsC05rxZ8c)
    * [MySQL - The Basics (17:16)](https://www.youtube.com/watch?v=Cz3WcZLRaWc)
    * [How to Save Data to MySQL Database (23:42)](https://www.youtube.com/watch?v=suVCVAuF5MU)


## Software to Install

- [MySQL Server](https://dev.mysql.com/downloads/) for **MacOS** (MySQL Community Server) or **Windows** (MySQL Installer for Windows) - Don't need Oracle Account, Select 'Developer Default'
- **VSCode Extension: MySQL** by Jun Han
- (For Windows Only) [Windows Subsystem for Linux](https://learn.microsoft.com/en-us/windows/wsl/install)

## In-Class Lab
* Setup Virtual Environments w/VS Code
* Scrape Twitter
* Manipulate w/JSON
* Save to MySQL Database