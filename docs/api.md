# Week: APIs
<hr>

![Map Image](images/img_iphs290_api_alvensia-angela-_N0srPVrfVk-unsplash.jpg)

## Overview

Data constantly flows constantly in networks under **two basic paradigms**. First, Information intended for humans exit computer networks via a interactive and/or visual interfaces. These include (a) a widows-based ***Graphical User Interfaces (GUIs)*** like those in MacOS and WindowsOS, and (b) a text-based *interactive REPL command line shell* (read-execute-print-loop) .

***Machine-to-Human GUIs*** are carefully designed to represent, architect, and sequence information to leverage human intuitions and cognitive processes. Unfortunately, programmatically scraping data from web GUIs can be slow, error-prone, fragile and (in many cases) impossible due to the limited resources, continual design updates, technical anti-scraping barriers and legal concerns. Web scraping can be viable for creating unique datasets based upon simpler open web sites or for harvesting smaller high-value data. 

To web scrape effectively, you will need to learn several core concepts. Content (HTML) and presentation (CSS) metatags organize data within a web page. Specific data within a web page can be uniquely identified and extracted using XPath notation and Beautiful Soup 4. Web frameworks and designs change frequently, are often deeply nested in human-unfriendly fashion and follow no universal pattern which makes web scraping a constant challenge.

Secondly, ***machine-to-machine API communications*** at the application layer are governed by strictly defined protocols like HTTP/REST and GraphQL passing data in well-structured file formats like JSON and XML. Machine-to-machine communications have the advantages of speed, scalability and programmable automation. Many websites make their data available via open and/or paid access using their own API. Unlike web pages, APIs are data exchange formats are dictated by centralized standards committees, rarely change and share universal best practices which makes exchanging data or creating unique datasets via API fast, efficient and reliable.

This week introduces common web scraping tools and programming practices. It is particularly useful to learn this in a collaborative lab environment since there are so many rules and exceptions to the rule it can be hard to quickly get a functional overview. We’ll also practice automating calls to popular REST API services to compile unique datasets. This includes learning the API for Twitter, Reddit and Instagram as well as the libraries to convert between JSON datafiles and internal Python data types like dicts{} and Pandas DataFrames.



## Applications

- [Monday]: 
    * [goto Web Scraping](./scraping.md)
- [Wednesday]: 
    * [goto Web Scraping](./scraping.md)
    * [Step-by-Step Guide to Making Your First Request to the New Twitter API](https://developer.twitter.com/en/docs/tutorials/step-by-step-guide-to-making-your-first-request-to-the-twitter-api-v2))
    * [Twitter API with Python (Complete Guide)](https://www.jcchouinard.com/twitter-api/)
- [Friday]: 
    * Review Map Projects
    * Setup Github Repos
    * [Automated Twitter Bot in Python (19:02)](https://www.youtube.com/watch?v=UGv_bJkF1kg)
    * Datacamp.com [Intermediate Importing Data in Python (2hrs) Chp 1-4](https://app.datacamp.com/learn/courses/intermediate-importing-data-in-python)


## Coding Practice

* Datacamp.com [Intermediate Importing Data in Python (2hrs)](https://app.datacamp.com/learn/courses/intermediate-importing-data-in-python)


## Additional References (Optional)

* REST vs GraphQL
* FastAPI & Uvicorn
* Postman vs Insomnia vs VSCode+Thunder
* Cloud, Microservices & SaaS