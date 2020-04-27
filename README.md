
## Extract, Transform, and Load (ETL) of Lawn Mowers' Data

This is developed to build database for consumer to assist their shopping experience. Consumers always compare prices, functions, and reviews of an item they wish to purchase before they make a purchasing decision. This particular database is consisting of name, description, price, review, and vendor of lawn mowers. 
Steps:
1.	The information is extracted from Walmart, Home depot, and Lowes's website.
  a.	We scraped the website using python BeautifulSoup and splinter.
  b.	Converted scraped data in pandas dataframe and wrote a csv.
2.	Retrieved the data form amazon using a API  https://amazon-price1.p.rapidapi.com/search 
a.	Converted scraped data in pandas dataframe and wrote a csv.
  3.	Combined all the csv files, cleaned the data using pandas and pushed into MongoDB database.
	 
This database is built by Jonathan Wu, Parag Patel, Preeti Chouksey, and Jaewon Kim.


