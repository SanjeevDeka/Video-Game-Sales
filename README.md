# Video-Game-Sales
An analysis of Video Game Sales by different genre, year, publisher, platform and region.

## Dataset description

This dataset contains a list of video games with sales greater than 100,000 copies. It was generated by a scrape of vgchartz.com.

Fields include:

- Rank - Ranking of overall sales

- Name - The games name

- Platform - Platform of the games release (i.e. PC,PS4, etc.)

- Year - Year of the game's release

- Genre - Genre of the game

- Publisher - Publisher of the game

- NA_Sales - Sales in North America (in millions)

- EU_Sales - Sales in Europe (in millions)

- JP_Sales - Sales in Japan (in millions)

- Other_Sales - Sales in the rest of the world (in millions)

- Global_Sales - Total worldwide sales.

The script to scrape the data is available at https://github.com/GregorUT/vgchartzScrape.

It is based on BeautifulSoup using Python.

There are 16,598 records. 2 records were dropped due to incomplete information.

Dataset taken from: https://www.kaggle.com/gregorut/videogamesales

## Data Cleaning

    Since there are only 3 records from 2017 and only 1 record from 2020, we'll remove those records as they are not correct representation for those 2 years.

    And also we need to remove the null values.

