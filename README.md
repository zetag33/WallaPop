# WallaPop
Given a term of search in WallaPop, a second-hand marketplace in Spain, extracts price and title and saves it into a csv
The code uses selenium because Wallapop loads its content via javascript so we render it using selenium.
The code enters to the main url of the site, goes to the search box, types the product that we want to search for.
Enters the url of results, presses the show more button in case it exists and displays all results, else just scraps the ones that are available.
Once it has pressed the button or not, it scrolls down, usually when there is a button the results are infinite so there is a parameter to set how many time we want to be recollecting data.
If the button doesn't exist it just scrolls until the end of the page.
Once it has collected all the data it saves it and writes into a structured csv with title and price.

The usability is to get:
  - Real time data market of a given category in wallapop.
  - We can research data of a wide range of products at the same time.

