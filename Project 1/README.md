# Scrapy_projects
 Scrapy is a fast high-level web crawling and web scraping framework (in python), used to crawl websites and extract structured data from their pages. It can be used for a wide range of purposes, from data mining to monitoring and automated testing. (see https://docs.scrapy.org/en/latest/)

Using python's library scrapy to scrape webpages
#### __Its uses:__
- Scrapy can be used to find specific words on web pages and return the webpage url
- It can be used to find specific information about products on multiple pages

# Project 1 Part i
## __Find Specific Words On Web Pages With Scrapy__

#### __In this example:__
- Lets say we want to search flyertalk articles for some information on booking hotels by the phone 
- The following code will crawl through each webpage and return a URL link if the word "phone", "hotel", "reservation" and "booked" has been mentioned on a webpage

### _Running the code in Anaconda Prompt_
- 1) scrapy startproject wordlist_scraper
- 2) cd wordlist_scraper
- 3) __scrapy crawl webcrawler > hotel_phone_project.csv__

# Project 1 Part ii
## __Analysing Web Pages Using Beautiful Soup__

- The second part of this code will be analysing the webpages returned from scrapy
- Using the library Beautiful soup we can scrape the whole page and search for specific words on the webpage

### __Process__
__1) Scrape Webpage__
- Use the library BeautifulSoup to scrape a webpage

__2) Clean Data__
- Remove HTML code, non-letters and change all to lower case

__3) Analyse Webpages__
- Create a function that flags if a particular word has been mentioned on the webpage 
- This enables us to see if multiple words have been mentioned on one webpage
___
