## Purpose:  
This app is designed to compile multiple website pricing data into one for an easy user shopping experience.  It is intended to ensure that the user can find the lowest price for a particular item, or search through categories of items to find a desired product to purchase.

## Additional Information:  
This app was created using macOS and ParseHub for web scraping.  

*API\_KEY*, *SECRET_KEY*, and tokens (tokens are keys for the latest scraped data) have been excluded from these commits to preserve security.  The live version posted on herokuapp includes full functionality, but would otherwise require creating your own project in Parsehub to be accepted by the app.

Databases to create for functionality:  
 1. pricecomp_test
 2. price_comparison

%run seed.py will need to be used to upload data from the parsehub projects in order to seed your database.

## Future implementation:  
Possibilities for the future include a wider range of ecommerce sources and expanded product selection.  Additionally, I plan to increase the efficiency of searchability of items and perfect product filter settings.

I will also plan to convert from using parsehub's api to having the web scraper developed using Beautiful Soup or another python based scraping tool.

## API:  
https://www.parsehub.com/

## Live Site!
https://retailcomp.herokuapp.com/