# Learn to Code: Introduction Web Scraping

Learn more Data Science Basics with our free Prep course!
http://bit.ly/gprepdata

Start Learning Web Development with our free Prep course!
http://bit.ly/gsoftprep

Get to this repo by typing in URL: **scrape.sage.codes**

### FAQ: 

- WIFI: `Galvanize Guest` | Password posted on walls 
- Bathrooms: Behind you down the hall to the left
- Kitchen outside back classroom door with Coffee & Tea!
- Snacks + water in back of room

## What this workshop is

A super friendly introduction to web scraping No previous experience expected, but some concepts may be confusing if you have never programmed before. If you get too lost let me know!

You can't learn EVERYTHING in ~2 hours. But you can learn enough to get excited and comfortable to keep working and learning on your own! 

- This course is for absolute beginners
- Ask Questions!
- Answer Questions!
- Help others when you can
- Its ok to get stuck, just ask for help!
- Feel free to move ahead
- Be patient and nice




## Setting up your computer


#### Please set up the following:

* A web browser to see what we're working on as others see it (Recommend Google Chrome: [chrome.google.com] (http://chrome.google.com))

* We will be using an online text editor for this workshop. You can sign up here: [https://repl.it/](https://repl.it/)


Well... that was easy! 


## Overview
The goal of this brief course is to provide you with a fun introduction to web Scraping Python.

#### Here's what we'll be doing:
* A primer on some technologies we're going to use
* Building a simple web scraper with Python
* I'll leave you with a coupl challenges at the end. You can try to complete them here if we have time, or try them at home!


## About me:
Hello I'm [Sage Elliott](http://sageelliott.com/). I'm a Technology Evangelist here at Galvanize! Previously I've worked as a software and hardware engineer with Startups and Agencies in Seattle, WA and Melbourne, FL. I love making things with technology! Currently learning more about computer vision with deep learning and helping a startup with a lane detection system for a self driving car application.

 I'm not a Galvanize Instructor, they're way better at teaching!

- Website: [sageelliott.com](http://sageelliott.com/)
- Twitter: [@sagecodes](https://twitter.com/@sagecodes)
- LinkedIn: [sageelliott](https://www.linkedin.com/in/sageelliott/) 
- Email: [sage.elliott@galvanize.com](mailto:sage.elliott@galvanize.com)


## About you!

Give a quick Intro!

- Whats your name?
- Whats your background?
- Why are you interested in Web Scraping?


## Web Scraping

### What is it?
I usually describe it as using a program to get data from the web by pulling content without an API(Application Program Interface).

Many sites have APIs you can connect to and use to pull data from.  Such as the [Twitter API](https://developer.twitter.com/en/docs.html). This is great! But sometimes you need data from a site that doesn't have an API. Thats what we're going to look at in this workshop. A lot of weather data can usually be pulled from an API.


### Where is it used?

Really any where you think it would be appriate to gather data. 

Some people I've met have built web scraper to look for jobs & find apartments.

Companies may search for email or contact information

Competitive analysis on a competing company, what prices do they have?

Realtors may scrape housing listings

Understand sentiment and words in reviews

Anytime you want data!


## Before we build

### HTML Basics

HTML is one of the main building blocks of the web!

###### Some common Tags(Elements):

- `<html>`	designates an HTML document
- `<head>`	contains undisplayed information about the document
- `<title>`	Creates a title for the document
- `<body>`	contains displayed information
- `<header>, <main>, <footer>` denotes which part of the page elements belong

- `<h1> - <h6>` create section headings (h1 biggest, h6 Smallest)
- `<p>` creates paragraphs
- `<a href=""></a>` (anchor), activates a link in the page
- `<ul>, <ol>` creates lists
  - `<li>` contains items in lists
- `<br>`	Inserts a single line break


###### Self-closing Tags:
most HTML tags require an opening and a closing tag. There are a few however that do not:

- `<img src="">` creates an image in the page
- `<br>` creates a break in the content
- `<input type="">` creates an input field
- `<hr>`	Creates a line in the page 

###### IDs, Classes
IDs and classes are very similar.
These are used to target specific elements(You'll see more examples in CSS section).
- `<h1 id="profile-header"></h1>`
- `<h1 class="subject-header"></h1>`

- IDs should only be used once on a page. IDs can also be used to bring the user to a specific part of the page. `your-site/#profile-picture` will load the page near the profile picture. 
- Classes can be used multiple times on a page. 


See More tags [here](https://www.w3schools.com/tags/ref_byfunc.asp)

Learn more HTML [here](https://www.w3schools.com/Html/)

	
#### Inspect element of a web page

- Go to a web page
- right click
- select `inspect element	`
- you should not see a pop up or frame showing the HTML of a web page.


### Python

We're going to be using python to do our web scraping.

Don't worry if you've never programmed in python or at all before, I will explain concepts along the way. And if you want me to repeat something just ask! We'll be doing a free intro to python workshop in January too if you want to go deeper! Or go through our [free data science prep material](https://www.galvanize.com/data-science-prep).

##### Requests

We will use the [Requests](http://docs.python-requests.org/en/master/) module to visit a URL and get web elements. 

##### Beautiful Soup

We will use [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/) is used to parse HTML and extract the information we need.


##### Pandas

We'll use [pandas](https://pandas.pydata.org/) to do some analysis and visulizations on our data 

##### NLTK

We'll use [NLTK](https://www.nltk.org/)(Natural Language Toolkit) to do some simple natural language processing on some text. 

##### Google Colab

We'll use google collab as our editor. It comes preinstalled with everything we need.


## Lets scrape data from the web!

Here's what we will do!

- Look at data tags
- write code to get data
- Look at scraped data
- get specific parts of the data
- transform the data for different use case
- minor visulizations for the data so we can understand it better
- Basic Sentiment Analysis on headlines to see how negative they are


#### Get Started:

- Open the notebook for this workshop [here](https://colab.research.google.com/drive/1UzyruU8hLorhEZb4RmHqh7pMQjt7mDeQ).

Make a copy by clicking `file` and `make copy` or `save to drive`


# Awesome, you now know the basics of web scraping!

Book mark this repo or the colla notebook and experiement with the code. Try a different website. 


## Challenges

- Install Python and run this scraper locally
- Scrape a different site
- Visiualise your data better using [matplotlib](https://matplotlib.org/)
- Save your data to a file or database
- Sentiment analysis on headlines like Google news


# Keep Learning

- [Free Data Science Prep](https://www.galvanize.com/data-science-prep)



- Checkout [Scrapy](https://scrapy.org/). Another python module foring doing web scraping. 




## Upcoming Events!

We host so many events! check out our [calendar](https://www.galvanize.com/events)

Visit the [Learn to code Seattle](https://www.meetup.com/Learn-Code-Seattle/) meetup for all upcoming events.


## What is Galvanize?
###### We are a community!


#### Immersive Bootcamp

- [Data Science](https://www.galvanize.com/data-science) - 5/6/19 - 8/2/19 

- [Software Engineer](https://www.galvanize.com/web-development) - 2/19/19 - 5/17/19

#### Part-Time Courses

- [Data Analytics](https://www.galvanize.com/part-time/data-analytics) 2/12/19 - 5/2/19
- [Python Fundamentals](https://www.galvanize.com/part-time/data-science-fundamentals) - 2/20/19 - 3/29/19

#### Co-working Space

[work in our building!](https://www.galvanize.com/entrepreneur)

#### We are a community

## Questions

Please feel free to reach out to me with any questions! Let me know what you're planning to do next and how I can help!


- Website: [sageelliott.com](http://sageelliott.com/)
- Twitter: [@sagecodes](https://twitter.com/@sagecodes)
- LinkedIn: [sageelliott](https://www.linkedin.com/in/sageelliott/) 
- Email: [sage.elliott@galvanize.com](mailto:sage.elliott@galvanize.com)






