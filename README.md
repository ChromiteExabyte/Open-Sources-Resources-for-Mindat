# Open-Source Resources for Mindat API, Earth Science, and Data Science

#### 🚧 This page is under construction 🚧

💡To find what you are looking for, click on the three lines in the upper right of this box to see headings. You can also scroll through this page at speed to find the links you are need. 

This page has resources, links, and guides relating to the Mindat.org mineralogy database and its new application program interface (API). This API establishes many practical affordances to those working with mineralogical data. The context, improvements, and changes relating to Mindat and the API can be found in paper "OpenMindat" which is linked to in the first section below. 

This is a community maintained repository and is not affiliated with any of the projects below. This GitHub repository does contain links to other resources and further resources, but this repository is not thoroughly cited yet. 








# 
# [OpenMindat: Open and FAIR mineralogy data from the Mindat database](https://rmets.onlinelibrary.wiley.com/doi/10.1002/gdj3.204 "OpenMindat Paper") 
### Authors: Xiaogang Ma, Jolyon Ralph, Jiyin Zhang, Xiang Que, Anirudh Prabhu, Shaunna M. Morrison, Robert M. Hazen, Lesley Wyborn, Kerstin Lehnert
#### Published in Geoscience Data Journal Volume 11, Issue 1 p. 94-104
- Accessible at https://rmets.onlinelibrary.wiley.com/doi/10.1002/gdj3.204 
- Open Access Paper; an inspiring research initiative!
- ⭐


# 
# [Mindat.org](Mindat.org)
## The world's most comprehensive mineral database and mineralogical reference website"
#
### ['How do I get my API Key?' article on Mindat.org by Jiyin Zhang](https://www.mindat.org/a/how_to_get_my_mindat_api_key "'How do I get my API Key?' article on Mindat.org by Jiyin Zhang")

Source: https://www.mindat.org/a/how_to_get_my_mindat_api_key

For those interested in using the API, there is an official tutorial on this webpage. As of April 10th 2024, the article has 3,125 views! 

**A user may generate an API key from their Mindat user page or from their  **



### [Mindat API Specification page in .YAML format through OpenAPI](https://api.mindat.org/schema/redoc/ "Mindat's API Access Points")

The specification for the API can be found at https://api.mindat.org/schema/redoc/ and is downloadable as a .YAML file. The Mindat API can be used with the R and Python packages as well as proprietary packages. 


###  Mindat.org's Current Search Functionality


- [Mindat's Full Search Menu](https://www.mindat.org/searchmenu.php)
- [Search Minerals By Chemistry](https://www.mindat.org/chemsearch.php)
- [Advanced Search](https://www.mindat.org/advanced_search.php)

#### Random Mineral, Random Locality 

The `Random Mineral` and `Random Locality` search options run a PHP script that generates a pseudorandom query.


### Downloading the full Mindat database 

The current footprint of the total Mindat database is measurable in gigabytes. While it is lighter than having all of those geomaterials in a backback, there are still considerations of storage and data handling that must be undertaken. 








#
# Machine Interfaces with the for the Mindat Database

The API for Mindat.org removes the need for web scraping. While you can use web-scraping methods on the Mindat.org website [example of old web scraper](https://github.com/MelorGloom/Crystal-Info-Scrapper/blob/main/main.py "Mindat Web Scraper on Github.com"), this method is now outdated. 

It is important to make a distinction in the usage of the Mindat API: querying and downloading data from the Mindat website is _not_ the same as data analytics and data science with the mineralogy data. 


## [OpenMindat - Quickly Retrieve Datasets from the 'mindat.org' API](https://cran.r-project.org/web/packages/OpenMindat/index.html "Mindat API R Package")
##### "An R package for querying and accessing open data from the Mindat API."
- Source: https://cran.r-project.org/web/packages/OpenMindat/index.html
- Author(s): Xiang Que [aut, cre], Xiaogang Ma [aut]
- "Allows access to the Mindat.org resources through the R programming language for data science activities."
- ⭐



## [OpenMindat Python](https://github.com/ChuBL/OpenMindat/wiki)
### An OpenMindat Python package in active development
### https://github.com/ChuBL/OpenMindat/wiki
- "This is a test version of the OpenMindat Python package, designed to facilitate querying and retrieving data on minerals and geomaterials from the Mindat API."
- An excellent resource with documentation.
- Author(s): Jiyin Zhang
- ⭐





### Downloading from Mindat.org with JavaScript in the Browser

🚧


### The Julia Programming Language for Mindat

The Julia Programming Language is capable of data science activities alongside or in parallel with Python and R. 

There exists an R package that allows calls to the Julia lang from R (https://cran.r-project.org/web/packages/JuliaCall/readme/README.html). 

There exists a Julia package that allows calls to Python package that may be interoperable with the Python Mindat package. The Julia package may be found at (https://juliahub.com/ui/Packages/General/PyCall). 
 
### Retrieval Augmented Generation (RAG) with the Mindat.org Database

🔡 There are many minerals and many mineral properties. Any large language model (LLM) to generate tokens in response to user text could, if connected to the internet, query the Mindat database for factual retrieval of geomaterial properties. If a user asks an LLM _"Is Sakuraiite a real mineral?"__, the LLM could call a simple function to the Mindat database to check. This kind of functionality could be built out through the [Microsoft Semantic Kernel](https://github.com/microsoft/semantic-kernel) or [Langchain](https://github.com/langchain-ai/langchain).

### The Rust Programming Language

🦀 

### Comma Separated Values (.csv) files through Excel, LibreOfficeCalc, 

🚧 Not all people interested in using the Mindat API are familar with programming languages. There are many great resources for folks to learn, however, the usecase of Mindat to .csv outputs is important. The fastest way right now to output .csv's is through R. 




# OpenMindat Usage on GitHub.com
## Mindat Data Collector

- Source: https://github.com/MisterSirCode/Mindat-Data-Collector
- Language: JavaScript
- 
https://github.com/ChuBL/How-to-Use-Mindat-API





## Mindat API on GitHub.com



### Mindat Data Collector

- Source: https://github.com/MisterSirCode/Mindat-Data-Collector
- Language: JavaScript



### Alpha Implementation of Mindat API in Python

- "A simple python example for the (alpha) version of the API. Requires an API key "
- Source: https://github.com/jolyonralph/mindat_api_test
- Author(s): Jolyon Ralph
- Python Programming Language
- 

### Asynchronous Fork of the above repository

- ""
- Source: https://github.com/MrHamel/mindat_api_test
- Author(s): Ryan Hamel
- Python Programming Language
- Unmaintained

##### Mindat.org web-scraping in Python (Outdated / Ineffecient)

- Source: https://github.com/MelorGloom/Crystal-Info-Scrapper
- PostgreSQL and Python


# Open Resources for Learning 📖

## Cross Disciplinary 

### Earth Data Science

- https://www.earthdatascience.org/
- Free Earth Data Science Courses & Textbooks
- Learn scientific programming, reproducible open science workflows and data science today.
- Python and Earth Data Science


## Geoscience 🪨🔨

#### Open Geology 

- Source: https://opengeology.org/
- An excellent collection of open source textbooks!

#### British & Exotic Mineralogy

- Source(s): https://www.c82.net/mineralogy/
- "All 2,242 illustrations from James Sowerby’s compendium of knowledge about mineralogy in Great Britain and beyond, drawn 1802–1817 and arranged by color."
- Interactive website 


## Computer Science and Data Science 🔬🧮


#### Learning Python for Data Science and Mineralogy 

Python is a programming language that is accessible and well-suited for data science. If you are new to computer programming, Python is an excellent choice. 

- FreeCodeCamp.com has an interactive "Scientific Computing With Python" course.
- The 'Python IDLE' is a programming environment associated with the Python language. 





### Data Science Resources Online



#### Data Science Books 
Advancing into Analytics: From Excel to Python and R (O’Reilly)
https://stringfestanalytics.com/book/





# What is this repository here?

. Please create a pull request if you can correct, clairfy, or expand on the resources above. :)

