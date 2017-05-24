# Python Web Scraping - Second Edition
This is the code repository for [Python Web Scraping - Second Edition](https://www.packtpub.com/big-data-and-business-intelligence/python-web-scraping-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781786462589), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
The internet contains the most useful set of data ever assembled, largely publicly accessible for free. However, this data is not easily reusable. It is embedded within the structure and style of websites and needs to be carefully extracted. Web scraping is becoming increasingly useful as a means to gather and make sense of the wealth of information available online.

This book is the ultimate guide to using the latest features of Python 3.x to scrape data from websites. In the early chapters, you’ll see how to extract data from static web pages. You’ll learn to use caching with databases and files to save time and manage the load on servers. After covering the basics, you’ll get hands-on practice in building a more sophisticated crawler using browsers, crawlers, and concurrent scrapers.


## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.



The code will look like the following:
```
from urllib.request import urlopen
from urllib.error import URLError
url = 'http://example.webscraping.com'
try:
 html = urlopen(url).read()
except urllib2.URLError as e:
 html = None
```

To help illustrate the crawling examples we have created a sample website at http://example.webscraping.com. The source code used to generate this website is available at http://bitbucket.org/WebScrapingWithPython/website, which includes instructions how to host the website yourself if you prefer. We decided to build a custom website for the examples instead of scraping live websites so we have full control over the environment. This provides us stability - live websites are updated more often than books and by the time you try a scraping example it may no longer work. Also a custom website allows us to craft examples that illustrate specific skills and avoid distractions. Finally a live website might not appreciate us using them to learn about web scraping and might then block our scrapers. Using our own custom website avoids these risks, however the skills learnt in these examples can certainly still be applied to live websites.

## Related Products
* [Web Scraping with Python](https://www.packtpub.com/big-data-and-business-intelligence/web-scraping-python?utm_source=github&utm_medium=repository&utm_campaign=9781782164364)

* [Flask: Building Python Web Services](https://www.packtpub.com/web-development/flask-building-python-web-services?utm_source=github&utm_medium=repository&utm_campaign=9781787288225)

* [Building RESTful Python Web Services](https://www.packtpub.com/application-development/building-restful-python-web-services?utm_source=github&utm_medium=repository&utm_campaign=9781786462251)

### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions.
