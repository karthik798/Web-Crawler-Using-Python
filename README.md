# Web-Crawler-Using-Python

## Website Used
```web
https://books.toscrape.com/
```
### Create a Project
```
scrapy startproject crawling

```
---
### Shell Commands
```
scrapy shell https://books.toscrape.com/catalogue/a-light-in-the-attic_1000/index.html
```
### Test Shell Commands
```
response.get("h3")
response.css("h3").get()
response.css("h3").get()
response.css("a::text").get()
response.css("a::text").getall()
response.css(".page-header").get()
response.xpath("//a/text()").extract()

```
---
### Run
```
scrapy crawl mycrawler

```
### To store Ouput in a File
```
scrapy crawl mycrawler -o output.json
```
---
