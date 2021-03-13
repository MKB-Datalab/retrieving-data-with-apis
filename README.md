# Basics on Retrieving Data with APIs

![](https://github.com/MKB-Datalab/retrieving-data-with-apis/blob/master/images/API_cover_Matthew_Henry_Burst.JPG)
source: [Matthew Henry](https://burst.shopify.com/@matthew_henry) from Burst

In this tutorial we give an overview of how to use APIs (Application Programming Interfaces) to retrieve data. Via API one is able to 
retrieve real time data as well as historical data. An example of interesting business application involves combining real time data 
together with historical data to predict  demand of products.

We start this tutorial with some basics on JSON (JavaScript Object Notation) files which are standard form for transferring data through 
APIs. After that we start exploring some APIs starting by a simple one: The [Open Movie database (OMDb) API]( http://www.omdbapi.com/). 
Then we take a look on how to get information from both [NS]( https://apiportal.ns.nl/) and KNMI Weer APIs ([Weerlive]( https://weerlive.nl/delen.php) and [meteoserver]( https://meteoserver.nl/)) . To close it we check out how to pull data 
from [Twitter]( https://twitter.com/home?lang=en).

## Data

Some JSON files built from data of OMDb are available [here](https://github.com/MKB-Datalab/retrieving-data-with-apis/tree/master/data/processed).

Models to be used to keep you APIs keys and Twitter credentials can be found in this [folder](https://github.com/MKB-Datalab/retrieving-data-with-apis/tree/master/notebooks). 

**Important**: Remember to list these files in your .gitignore file to keep them safe when making your code available in GitHub, for example.

## :wrench: Tools

* [`requests`](https://requests.readthedocs.io/en/master/): HTTP library for Python that allows us to send HTTP requests in a simple way.
* [`python-twitter`](https://python-twitter.readthedocs.io/en/latest/index.html), a python wrapper around the Twitter API.

## :computer: Install requirements
* Install requirements using `pip install -r requirements.txt`.
  * Make sure you use Python 3.
  * You may want to use a virtual environment for this.

-------------------------------------
[:arrow_backward: **Back to repository main page**](https://github.com/dpbac/test_mkb_knowledge_repo)