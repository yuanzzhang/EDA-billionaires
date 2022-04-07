# Final Project

## Source and Host
The source for the billionaires.csv dataset stems from Forbes World’s Billionaires lists from 1996-2014. Scholars from the Peterson Institute for International Economics contributed more variables to the dataset regarding specific billionaires. The host of the data is from the CORGIS Dataset Project. https://think.cs.vt.edu/corgis/csv/billionaires/

## Number of variables and observations
There are 22 variables and 2614 observations.

## CodeBook
### Format: Variable Name, type, description, example

name	String  
  The name of the billionaire.	"Bill Gates"
  
rank  Integer  
  The rank of this billionaire compared to the rest of the billionaires reported on. A lower rank means they make more money. 1
  
year	Integer  
  The year that data about this billionaire was collected.	1996
  
company.founded	Integer  
  The year that the company was founded.	1975
  
company.name	String  
The name of the company.	"Microsoft"
  
company.relationship	String	
  The billionaires relationship to the company.	"founder"
  
company.sector	String	
  The sector of the business, or what segment of the economy they fit into.	" Software"
  
company.type	String	
  The type of business for this company.	"new"
  
demographics.age	Integer  
  The current age of the billionaire. Ages that are represented as -1 stand for ages that were not available in the data that was collected.	40
  
demographics.gender	String	
  A string representing their gender.	"male"
  
location.citizenship	String	
  The name of the country that this billionaire has citizenship with.	"United States"
  
location.country.code	String	
  the 3-letter country code of the country where this billionaire has citizenship. "USA"

location.gdp	Float	
  The "Gross Domestic Product" of the country where the billionaire has citizenship. This is one of the primary indicators used to gauge the health of a country's economy. It represents the total dollar value of all goods and services produced over a specific time period; you can think of it as the size of the economy.	8100000000000.0
  
location.region	String	
  The region of the world where this billionaire lives.	"North America"

wealth.type	String	
  The type of billionaire that they are.	"founder non-finance"
  
wealth.worth in billions	Float  
  The number of billion of dollars that this billionaire is worth.	18.5
  
wealth.how.category	String  
  A category representing where their money came from.	"New Sectors"
  
wealth.how.from emerging	Boolean  
  Whether the money came from emerging markets.	True
  
wealth.how.industry	String	
  The specific industry this billionaire profited from.	"Technology-Computer"
  
wealth.how.inherited	String  
The way that this money was inherited (or not inherited). Inheritance can come from a spouse, the father, or from multiple generations within a family (either 3, 4, or 5+).	"not inherited"  

wealth.how.was founder	Boolean  
  Whether the billionaire was the founder of their company.	True