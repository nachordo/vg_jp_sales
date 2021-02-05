# Japanese Video Game Sales - A Web scraping & RegEx exercise in Python

I present here a small and fun exercise with high doses of nerdiness. This is done to practice web scraping techniques and regular expressions. **The objective: to build an interesting database of weekly hardware and the top 30 software video game sales in Japan.**

Here is the premise. The user [Chris1964](https://www.resetera.com/members/chris1964.2713/) in the [ResetEra forums](https://www.resetera.com/)  collects and posts each week the sales that appears in the Famitsu Magazine (previously Media Create as well but they stopped giving these numbers). This publication lists the weekly top 30 video game sales and the console sales each week. All the weekly posts are listed in another post. 

These posts are written with the same style, so this constitutes a nice Web scraping & RegEx exercise.

In this repo I show all the steps to create functions in order to perform recursively the data mining using `BeautifulSoup` and `RegEx`. After these steps you will be able to obtain a weekly software and hardware datasets to play with. I divided the exercise in two notebooks: [one to obtain the software data](webscraping/sales-vg-sw.ipynb) and [another to mine the hardware](webscraping/sales-vg-sw.ipynb). 


![Tom Nook](https://i1.wp.com/n64josh.com/wp-content/uploads/2020/04/tom-nook-moneyjpg.jpeg?resize=664%2C335&ssl=1)
