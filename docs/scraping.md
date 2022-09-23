# Week: Scraping 
<hr>

![Map Image](images/img_iphs290_scrape_alvensia-angela-_N0srPVrfVk-unsplash.jpg)

## Overview

Data is the Alpha and Omega of Data Science, Machine Learning and Deep Learning. The creativity, expressiveness and strength of your analysis will be bounded by the data you have. The quality of your dataset can be measured along many dimensions including the type/number of features, originality, number of datapoints, accuracy, coherence, etc.

While there are a rapidly growing number of public datasets, they often are best used for tutorials, training and establishing baseline metrics. It is extremely difficult to create new, innovative and meaningful data analysis based upon datasets already mined by others. This week we study Web Scraping and APIs so you will be able to create your own unique datasets based upon the wide variety and vast quantity of information available on the Web. 

Data constantly flows constantly in networks under **two basic paradigms**. First, Information intended for humans exit computer networks via a interactive and/or visual interfaces. These include (a) a widows-based ***Graphical User Interfaces (GUIs)*** like those in MacOS and WindowsOS, and (b) a text-based *interactive REPL command line shell* (read-execute-print-loop) .

***Machine-to-Human GUIs*** are carefully designed to represent, architect, and sequence information to leverage human intuitions and cognitive processes. Unfortunately, programmatically scraping data from web GUIs can be slow, error-prone, fragile and (in many cases) impossible due to the limited resources, continual design updates, technical anti-scraping barriers and legal concerns. Web scraping can be viable for creating unique datasets based upon simpler open web sites or for harvesting smaller high-value data. 

To web scrape effectively, you will need to learn several core concepts. Content (HTML) and presentation (CSS) metatags organize data within a web page. Specific data within a web page can be uniquely identified and extracted using XPath notation and Beautiful Soup 4. Web frameworks and designs change frequently, are often deeply nested in human-unfriendly fashion and follow no universal pattern which makes web scraping a constant challenge.

Secondly, ***machine-to-machine API communications*** at the application layer are governed by strictly defined protocols like HTTP/REST and GraphQL passing data in well-structured file formats like JSON and XML. Machine-to-machine communications have the advantages of speed, scalability and programmable automation. Many websites make their data available via open and/or paid access using their own API. Unlike web pages, APIs are data exchange formats are dictated by centralized standards committees, rarely change and share universal best practices which makes exchanging data or creating unique datasets via API fast, efficient and reliable.

This week introduces common web scraping tools and programming practices. It is particularly useful to learn this in a collaborative lab environment since there are so many rules and exceptions to the rule it can be hard to quickly get a functional overview. We’ll also practice automating calls to popular REST API services to compile unique datasets. This includes learning the API for Twitter, Reddit and Instagram as well as the libraries to convert between JSON datafiles and internal Python data types like dicts{} and Pandas DataFrames.



## Applications

- [Monday]: 
    * [Web Scraping Basics in Python (19:47)](https://www.youtube.com/watch?v=myAFVM7CxWk)
    *  Datacamp.com [Web Scraping in Python (2hrs) Chp 1 & 2](https://app.datacamp.com/learn/courses/web-scraping-with-python)
- [Wednesday]: 
    * [Beautiful Soup: Build a Web Scraper With Python](https://realpython.com/beautiful-soup-web-scraper-python/)
    *  Datacamp.com [Web Scraping in Python (1hrs) Chp 3](https://app.datacamp.com/learn/courses/web-scraping-with-python)
    * [goto API](./api.md)
- [Friday]: 
    * [goto API](./api.md)


## Software to Install

* [VSCode](https://code.visualstudio.com/download)
* [Thunder VS Code Plugin for APIs](https://marketplace.visualstudio.com/items?itemName=rangav.vscode-thunder-client)
* [Virtual Environments with venv](https://voxel51.com/docs/fiftyone/getting_started/virtualenv.html)
* 
## New Python Libraries

* [virtualenv](https://docs.python-guide.org/dev/virtualenvs/)
* [requests.py](https://requests.readthedocs.io/en/latest/)
* [Beautiful Soup 4](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
* [lxml](https://lxml.de/)
* [Selenium](https://github.com/SeleniumHQ/selenium)
* [webdriver-manager](https://github.com/SergeyPirogov/webdriver_manager)
* (Optional) [Scrapy](https://github.com/scrapy/scrapy)


## In-Class Lab
* [HTML & CSS Crash Course Tutorial #7 - Chrome Dev Tools](https://www.youtube.com/watch?v=25R1Jl5P7Mw)
* [How to find xpath in Chrome (4:06)](https://www.youtube.com/watch?v=JanCuJSAzhc)
* [Beautiful Soup: Build a Web Scraper With Python](https://realpython.com/beautiful-soup-web-scraper-python/)
* (Reference: Table at top of article) [Practical XPath for Web Scraping](https://www.scrapingbee.com/blog/practical-xpath-for-web-scraping/)
* [Crash Course Scraping with XPath+Selenium](https://www.youtube.com/watch?v=jraDTvKLLvY)
* [Books.toscrape.com](https://books.toscrape.com/ )
* [XPather](http://xpather.com/ 
)
* Chrome Extension: [Google Chrome Free Web Scraper](https://chrome.google.com/webstore/detail/web-scraper-free-web-scra/jnhgnonknehpejjnehehllkliplmbmhn?hl=en) [Tutorial](https://www.youtube.com/watch?v=BRyfnI6Jtzs )
* Chrome Extension: [Instant Data Scraper](https://chrome().google.com/webstore/detail/instant-data-scraper/ofaokhiedipichpaobibbnahnkdoiiah?hl=en-US)
* [Selinum Browser Automation](https://www.youtube.com/watch?v=SPM1tm2ZdK4&t=3s)


## Optional Additional References

* [PEP8 Style Guidelines](https://peps.python.org/pep-0008/)
* [Virtual Environments in Python (13:32)](https://www.youtube.com/watch?v=IAvAlS0CuxI)
* [Always Check for the Hidden API when Web Scraping (11:49)](https://www.youtube.com/watch?v=DqtlR0y0suo)
* [Web Scraping with Professional Proxy Servers (32:25)](https://www.youtube.com/watch?v=hh8UHmkymik)
* [Selenium Browser Automation in Python (21:37)](https://www.youtube.com/watch?v=SPM1tm2ZdK4)
* [XPath Test Evaluator](https://www.freeformatter.com/xpath-tester.html#xpath-examples)