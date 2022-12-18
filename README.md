# Beer Project

## Punk API
You are going to build a beer wiki that uses data from the Punk API (https://punkapi.com/documentation/v2). The website should consist of three differenta views (pages)(see below for information on the different pages). The pages do not necessarily have to be individual HTML documents. A document that uses DOM manipulation to show different (pages) content is perfectly fine. The requirement is that ONE page (and not fler!) should be displayed at a time. In addition to the requirements specified below, you have a free hand (for example, regarding design).


## Kravspecifikation

### G-requirements
#### Landing Page (Random beer)
•	The user should be able to randomize a beer by pressing a button, for example.
•	The name and image of the random beer should be seen in a "card" (see below for examples).


![alt text](BeerCard.jpg)

•	The user should be able to press "See More" to get to the "Beer Info Page" (See further down for info).


#### Search Page
•	Users should be able to search for a beer using its name.
•	The page should use a form.
•	The result of the search should be displayed in a list (only the names of the beer).
•	The list may contain a maximum of 10 results. If more than 10 search results are available, the list should be paginated.
•	If you click on a search result, you should go to the Beer Info Page for that beer.



#### Beer Info Page
•	This page should only go to any of the pages described above.
•	On this page, the user should be able to get detailed information about a specific beer.
•	The page should contain at least:
    o	Description
    o	Image
    o	Alcohol by volume
    o	Volume
    o	Ingredients
    o	Hops
    o	Food pairing
    o	Brewers tips


### Bonus (VG-krav)

#### Search Page
•	Users should be able to perform advanced searches.
•	A user should be able to search on one of these or a combination of these criteria:
    o	Name
    o	Hops
    o	Malt
    o	Brewed Before & Brewed After
    o	ABV Greater Than & ABV Less Than
•	The search form should include relevant validation
•	The page should cache previously visited pages of search results. That is, if you go from page 1 to page 2 and then back to page 1 of the search results, no further request should be made.

