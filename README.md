# Web-scraper-for-ecommerce-website-daraz.com.np-

 
## If this violates any copyright or raises any legal issues. Please inform me. It will be removed.

This the link to a data corpus from daraz.com.np
`https://github.com/nOOBIE-nOOBIE/Daraz-online-shopping-data-corpus/`


## Notes:
     Operating System: Linux
     Language:         python3
     libraries:        Scrapy, system, chdir   

     This scraper was purely  built for research purpose. 


#### you may need to edit the code at daraz/daraz/darazall.py. If the website changes in future


Please note that you might need to make some changes to the scraper 
if in future the interface of the daraz.com.np is 
changed.( the scraping is totally based on CSS)

### Guides to use the scrapper
 1. clone this repository to your computer
 2. Launch terminal
 3. Navigate to the folder with file scrapy.cfg
 4. Enter this code
 `scrapy crawl darazall -o data.csv`

 This is the sample code

 `scrapy crawl darazall -o data.csv`

 ### Explanation of code :  
   *  *It will simply store all the scraped data into the data.csv file
 
### Following data will be extracted
 #### [Product,Category, Brand, Price ,Seller_name, Average_Product_rating, Buyer_comments, Buyer_comment_title, Buyer_product_review] . 
