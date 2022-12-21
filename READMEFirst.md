# HSG-Project
Project for the Programming with Advanced Computer Languages class at HSG

This project is a Web Scraper build with python. It shows the latest articles of the websites being scraped and return the main headlines. Currentlly, the code shows the headlines for both "The Onion" (https://www.theonion.com/) and BBC (https://www.bbc.com/news). It works by first emulating a browser and then grabbing the corresponding html header for each website. Additional websites can be added to the code by siply adjusting the HTML parsing to the format used by the target website. That is, in place of

for h in soup.findAll('h3', class_='gs-c-promo-heading__title')

The h3 may be changed to div, h2 or others, and the class object should also change with each new website. To see the correct class and header it is necessary to inspect the html elements of the targeted website

To run the program, just open a jupyther notebook and click run. The code is written so that nothing more is needed to run it

Group: Victor Lara Santos and Basil Gemperle
