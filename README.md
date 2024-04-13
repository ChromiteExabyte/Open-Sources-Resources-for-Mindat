# Open-Source Resources for Mindat API, Earth Science, and Data Science

**🚧 This page is under construction 🚧**

This is a community maintained repository and is not affiliated with any of the projects below; see the hyperlinks to the project sources for full explanations.

### Mineralogical Data from Mindat.org with Python & R

If you are using Python or R for Data Science, there are completed packages ready for use with the Mindat API!

- [OpenMindat CRAN Package](https://cran.r-project.org/web/packages/OpenMindat/index.html "Mindat API R Package")
- [OpenMindat Python Package](https://github.com/ChuBL/OpenMindat/wiki)

### Mineralogical Data from Mindat.org without the Python or R Programming Languages

Right now the Mindat API is most accessible through R and Python. However, anyone who can use excel can get started with Python or R. Unlike Excel, these programming languages are free. 

#### Mindat.org through Python for absolute Beginners

First, download the Python programming language at Python.org. Next, visit this URL (https://colab.research.google.com/github/ChuBL/How-to-Use-Mindat-API/blob/main/How_to_Use_Mindat_API.ipynb ) With no programming experience whatsoever, you can follow the steps within this Jupyter Notebook to get started with the API. 


# 
# [OpenMindat: Open and FAIR mineralogy data from the Mindat database](https://rmets.onlinelibrary.wiley.com/doi/10.1002/gdj3.204 "OpenMindat Paper") 
### Authors: Xiaogang Ma, Jolyon Ralph, Jiyin Zhang, Xiang Que, Anirudh Prabhu, Shaunna M. Morrison, Robert M. Hazen, Lesley Wyborn, Kerstin Lehnert
#### Published in Geoscience Data Journal Volume 11, Issue 1 p. 94-104
- Accessible at https://rmets.onlinelibrary.wiley.com/doi/10.1002/gdj3.204
 
- Open Access Paper; an inspiring research initiative!
- The Mindat API and improvements to the data establishes many practical affordances to those working with mineral information !
- ⭐

#
# [Mindat.org](Mindat.org)
_The world's most comprehensive mineral database and mineralogical reference website"_


### ['How do I get my API Key?' article on Mindat.org by Jiyin Zhang](https://www.mindat.org/a/how_to_get_my_mindat_api_key "'How do I get my API Key?' article on Mindat.org by Jiyin Zhang")

Source: https://www.mindat.org/a/how_to_get_my_mindat_api_key

- The first step in getting started with the Mindat API
- The article "How do I get my API Key?" explains how a user can obtain a key
- An API "key" is a long string of letters and numbers that uniquely identifies the user when they are interacting with the Mindat API. 
- The article has several thousand views (which is a metric to the interest in the extended function of Mindat). 


### [Mindat API Specification page in .YAML format through OpenAPI](https://api.mindat.org/schema/redoc/ "Mindat's API Access Points")

Source: https://api.mindat.org/schema/redoc/

- The API endpoints are downloadable as a .YAML file above and are in OpenAPI format
- Start here if you are a developer or in need of accessing the Mindat API endpoints directly. 


###  Mindat.org's Current Search Functionality

- Depending on context, you may not need to use the full search functions of the Mindat API! See the advanced search functions below for 
 
 - [Mindat's Full Search Menu](https://www.mindat.org/searchmenu.php)
 - [Search Minerals By Chemistry](https://www.mindat.org/chemsearch.php)
 - [Advanced Search](https://www.mindat.org/advanced_search.php)


### Downloading the full Mindat database 

The current footprint of the total Mindat database is measurable in gigabytes. It's lighter than a backpack full of those same geomaterials !

🚧 Items I would like to add to this guide: 
- Downloading the entire Mindat database to a local copy.
- Verifying a local database has the most correct information
- 




#
# Machine Interfaces with Mindat Database

It is important to make a distinction in the usage of the Mindat API: querying and downloading data from the Mindat website is _not_ the same as data analytics and data science with the mineralogy data. R and Python allow for both. 


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



## Comma Separated Values (.csv) from the Mindat 

🚧 Not all people interested in using the Mindat API are familar with the programming of digital computers. There are many great resources for folks to learn and anyone interested can get started within an hour. However, the usecase of Mindat to .CSV outputs is important and I think that the Mindat API can facilitate this. At present, Python and R are the only solid options (as I understand).







### Downloading from Mindat.org with JavaScript in the Browser

🚧

The API for Mindat.org removes the need for web scraping. While you can use web-scraping methods on the Mindat.org website [example of old web scraper](https://github.com/MelorGloom/Crystal-Info-Scrapper/blob/main/main.py "Mindat Web Scraper on Github.com"), this method is now outdated and it. 


### The Julia Programming Language for Mindat

The Julia Programming Language is capable of data science activities alongside or in parallel with Python and R. Anything that can be used for data science activities with the Mindat API should be used for data science activities !

There exists an R package that allows calls to the Julia lang from R (https://cran.r-project.org/web/packages/JuliaCall/readme/README.html). 

There exists a Julia package that allows calls to Python package that may be interoperable with the Python Mindat package. The Julia package may be found at (https://juliahub.com/ui/Packages/General/PyCall). 
 
### Retrieval Augmented Generation (RAG) with the Mindat.org Database

🔡 There are many minerals and many mineral properties. Any large language model (LLM) to generate tokens in response to user text could, if connected to the internet, query the Mindat database for factual retrieval of geomaterial properties. If a user asks an LLM _"Is Sakuraiite a real mineral?"__, the LLM could call a simple function to the Mindat database to check. This kind of functionality could be built out through the [Microsoft Semantic Kernel](https://github.com/microsoft/semantic-kernel) or [Langchain](https://github.com/langchain-ai/langchain), or another tool altogether.

### The Rust Programming Language

🦀 Rust is a systems level language. Rust in the browser may be usable through 



# OpenMindat Usage on GitHub.com
## Mindat Data Collector

- Source: https://github.com/MisterSirCode/Mindat-Data-Collector
- Language: JavaScript





## Alpha Implementation of Mindat API in Python

- "A simple python example for the (alpha) version of the API. Requires an API key "
- Source: https://github.com/jolyonralph/mindat_api_test
- Author: Jolyon Ralph
- Outdated with the full release of the Mindat API
- Python Programming Language

### An Asynchronous Fork of the above repository

- Source: https://github.com/MrHamel/mindat_api_test
- Author(s): Ryan Hamel
- Python Programming Language
- Outdated with the full release of the Mindat API

## Mindat.org web-scraping in PostgreSQL Python (Outdated / Ineffecient)

- Source: https://github.com/MelorGloom/Crystal-Info-Scrapper
- PostgreSQL and Python
- Made redundant with the MindatAPI, which allows for this task to be done much more effeciently! 


# Open Resources for Learning 📖


### Earth Data Science

- https://www.earthdatascience.org/
- Free Earth Data Science Courses & Textbooks
- Learn scientific programming, reproducible open science workflows and data science today.
- Python and Earth Data Science




### Open Geology Textbooks

- Source: https://opengeology.org/
- An excellent collection of open source textbooks!

### British & Exotic Mineralogy

- Source(s): https://www.c82.net/mineralogy/
- "All 2,242 illustrations from James Sowerby’s compendium of knowledge about mineralogy in Great Britain and beyond, drawn 1802–1817 and arranged by color."
- Interactive website 


### Learning Python for Data Science and Mineralogy 

Python is a programming language that is accessible and well-suited for data science. If you are new to computer programming, Python is an excellent choice. 

- FreeCodeCamp.com has an interactive "Scientific Computing With Python" course.
- The 'Python IDLE' is a programming environment associated with the Python language. 


#### Data Science Books 
Advancing into Analytics: From Excel to Python and R (O’Reilly)
https://stringfestanalytics.com/book/





# What is this repository here?

This repository is a student practicing documentation. The OpenMindat paper and Mindat API are really exciting and interesting. There are many excellent and amazing things that are still to come of this resource being made accessible. Please create a pull request if you can correct, clairfy, or expand on the resources above. :)

