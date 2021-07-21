# Michelin Star Restaurants MongoDB

created by Sunny Kim and Elizabeth Odundo

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

## Project Description

The Michelin Star Restaurant database project coalesces data from three different sources (.csv files, API calls, and web scraping) and creates a non-relational database using MongoDB. The completed database contains three collections (one for each level of Michelin star ranking) and will hold the following information on each Michelin star restaurant: restaurant name, city, region, type of cuisine, url to website, nearest hotel/lodging, and specialty dishes. 


## Data

* [Michelin restaurant data](https://www.kaggle.com/jackywang529/michelin-restaurants) from Kaggle
* Google Places API
* [Michelin Guide](https://guide.michelin.com/en/restaurants)

### Built With

* Jupyter Notebook 
* Pymongo
* Pandas
* Splinter
* BeautifulSoup
* Requests

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/sunwoo-kim20/etl-michelin-restaurants.git
   ```
2. Install Python Libraries
   ```sh
   !pip install pandas
   !pip install requests
   !pip install json
   !pip install splinter
   !pip install bs4
   !pip install webdriver_manager.chrome
   !pip install time
   !pip install pymongo
   ```
3. Create a Google Cloud Platform API key and add unique key to a config.py file
   ```sh
   g_key = "YOUR KEY"
   ```



<!-- USAGE EXAMPLES -->
## Usage

This application allows users to grab data on Michelin star restaurants efficiently through MongoDB queries. 

![Screenshot of Michelin star documents in MongoDBCompass](https://github.com/sunwoo-kim20/etl-michelin-restaurants/blob/main/docs/images/michelin-db-screenshot.png?raw=true)
![Screenshot of calling data through pymongo](https://github.com/sunwoo-kim20/etl-michelin-restaurants/blob/main/docs/images/document-calls.png?raw=true)



<!-- CONTACT -->
## Contact

Sunwoo Kim - s.kim32415@gmail.com

Project Link: [https://github.com/sunwoo-kim20/sqlalchemy-challenge](https://github.com/sunwoo-kim20/sqlalchemy-challenge)

