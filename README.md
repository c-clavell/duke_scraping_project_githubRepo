# duke_webscraping_project

In this project, the goal is for you to build a web scraping tool from scratch. This web scraper should, extract specific information, transform the data into a CSV file and then save it to disc.

For this project you will use  Scrapy, a powerful web scraping tool in Python.


The target web site is https://edurank.org/geo/ca/ . It contains information about the Canadian's universities and their ranking. The information extracted is: university name, ranking in Canada and the world, year founded location ,enrollment and acceptance rate.

The project uses the module requests to get the text contents of the page. The contents are then written to a local file called universities.html .

The information extracted is then written into a local csv named top_universities.csv .

IMPORTANT!
Apparently the web site changes its html code when scrapping is detected. Careful if connecting and trying to get the website's contents multiple times because the html code might be different.