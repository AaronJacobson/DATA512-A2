# DATA512-A2

## Data Description for page_data.csv

| Feature | Description|
|---------|------------|
| Page | The name of the page |
| Country | The name of the country the page is for |
| rev_id | The revision id of the page to be evaluated |

## Data Description for WPDS_2020_data - WPDS_2020_data.csv

| Feature | Description|
|---------|------------|
| FIPS | The name of the page |
| Name | The name of the country the page is for |
| Type | The type of data in the row. Will be one of the following: World, Sub-Region, Country |
| TimeFrame | The year which the population corresponds to |
| Data (M) | The population of the country in millions |
| Population | The population of the country |

## Data Description for wp_wpds_countries-no_match.csv

| Feature | Description|
|---------|------------|
| Page | The name of the page |
| Country | The name of the country the page is for |
| rev_id | The revision id of the page to be evaluated |
| FIPS | The name of the page |
| Name | The name of the country the page is for |
| Type | The type of data in the row. Will be one of the following: World, Sub-Region, Country |
| TimeFrame | The year which the population corresponds to |
| Data (M) | The population of the country in millions |
| Population | The population of the country |

## Data Description for wp_wpds_politicians_by_country.csv

| Feature | Description|
|---------|------------|
| Page | The name of the page |
| Country | The name of the country the page is for |
| rev_id | The revision id of the page to be evaluated |
| quality | The estimated page quality of the page |
| Population | The estimated population of the country for the page in 2019 |

## Reflections and Implications

Given we're only working with english language wikipedia articles I expected most non-anglo countries to have very few articles, and fewer good ones. What I found aligns with that in general, though the exception is that the countries with a high number of articles per capita are particularly small countries that happen to have a decent amount of tourism form the anglo world. Additionally, the countries that have the highest proportion of their articles rated GA or FA are usually countries that don't speak english but are in the news a lot, like North Korea and Syria.

The first thing to do to expand on this analysis is to use different language versions of Wikipedia and both look at, for example, French politicians and in French Wikipedia, and look at the difference between articles about French politicians in French vs in English. Another task would be to look at non-Wikipedia articles in countries that don't use Wikipedia much but may use other, similar, websites in their own languages. 