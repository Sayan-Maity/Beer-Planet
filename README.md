# Beer Planet

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) 
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Netlify Status](https://api.netlify.com/api/v1/badges/43eb9b9f-4944-4196-9e6a-f06cde9a10d9/deploy-status)](https://app.netlify.com/sites/benevolent-dolphin-d3747e/deploys)

> ```Beer Planet``` is a onestop solution for all the information required before getting a mug 🍺.

Author : [Sayan Maity](sayancr777@gmail.com)

## Punk API
You are going to build a beer wiki that uses data from the Punk API (https://punkapi.com/documentation/v2). The website should consist of three differenta views (pages)(see below for information on the different pages). The pages do not necessarily have to be individual HTML documents. A document that uses DOM manipulation to show different (pages) content is perfectly fine. The requirement is that ONE page (and not fler!) should be displayed at a time. In addition to the requirements specified below, you have a free hand (for example, regarding design).


## Specification

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

## Built with
<img src="https://img.shields.io/badge/html5%20-%23E34F26.svg?&style=for-the-badge&logo=html5&logoColor=white"/>  <img src="https://img.shields.io/badge/css3%20-%231572B6.svg?&style=for-the-badge&logo=css3&logoColor=white"/> <img src="https://img.shields.io/badge/javascript%20-%23323330.svg?&style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/> 

- **Frontend**: HTML, CSS, Javascript
- **Version Control**: Git
- **Hosting**: Netlify, Github Pages

## Setup and Installation
Fork and Clone this project. Make sure you have git installed. On the terminal, navigate to your workspace directory and run it
​
## License
This project is licensed under the MIT license.