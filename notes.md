# Make spider
    -  scrapy genspider bookspider books.toscrape.com
       -  include website wanted for scraping
    -  pip install ipython
       -  different terminal
       -  shell = ipython
          -  in settings
       -  scrapy shell
          -  run command

# Xpath
   -  response.xpath("//div[@id='product_description']/following-sibling::p/text()").get(),

# Converting Files
   - scrapy crawl <name> -O bookdata.json
   - scrapy crawl <name> -O bookdata.csv
   - scrapy crawl <name> -o bookdata.csv
     - To append to file

# Scrape Ops
   -  Lets you get a bunch of headers when making request to scrape website
   -  api_key = 29eb6379-33a8-41c9-969c-b344282b3c1d



