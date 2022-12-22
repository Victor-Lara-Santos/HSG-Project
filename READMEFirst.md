# HSG-Project
Project for the Programming with Advanced Computer Languages class at HSG

This project is a Web Scraper build with python. It shows the latest articles of the websites being scraped and return the main headlines. Currentlly, the code shows the headlines for "The Onion" (https://www.theonion.com/), BBC (https://www.bbc.com/news), Reuters (https://www.reuters.com/news/archive) and Bloomberg (https://www.bloomberg.com/markets). There are two approaches in the file. The first (Reuters and The Onion), works by getting the neccesary html items, equalizing the number of items on each of the created arrays and using pandas to print the solution. The second works by first emulating a browser and then grabbing the corresponding html header for each website. Additional websites can be added to the code by simply adjusting the HTML parsing to the format used by the target website. That is, in place of

for h in soup.findAll('h3', class_='gs-c-promo-heading__title')

The h3 may be changed to div, h2 or others, and the class object should also change with each new website. To see the correct class and header it is necessary to inspect the html elements of the targeted website

As said above, The Reuters and The Onion scrapper is similar to the one used for BBC and Bloomberg, but it uses panda to organize the summary, title and url of the articles

To run the program, just open a jupyther notebook and click run. The code is written so that nothing more is needed to run it

bbc_headline_scraper from indently in github was used as an inspiration and tutorial for BBC and Bloomberg scrapers
Seungjun-Data-Science used as inspiration and tutorial for Reuters and The Onion scrapers

Due to differences on html structures between the varying websites, it was not possible to use only one solution to all of them; not only that, but even within the same solution there are differences due to how each website is structured. For example, the solution used for both The Onion and Reuters is the same, but it was not possible to grab the summaries for each article from The Onion, while with Reuters it was possible.

I would also like to add that I really liked the class and that I'm extremely happy for taken it, since I wanted to learn how to code for a long time but was never able to actually do something, but with the approach and exercises used during the class I'm finally able to get a much better grasp of programming.

Group: Victor Lara Santos
