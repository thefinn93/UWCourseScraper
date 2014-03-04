UWCourseScraper
===============

A scraper for the University of Washington's horrible course listing's pages.
Mostly written during a class.

Dependencies
----------
* [Requests](http://www.python-requests.org)
* [BeautifulSoup](http://www.crummy.com/software/BeautifulSoup/) 4+

Usage
----------
After installing the dependencies, run scraper.py. It will scrape the course
list from the Bothell campus, then the schedule for Spring 2014 for each major,
outputting the whole thing to stdout in JSON format. Proper modularity and
packaging coming eventually...

Help! It's broken!
---------
File an issue. Or shut up and fix it, then make a pull request.
