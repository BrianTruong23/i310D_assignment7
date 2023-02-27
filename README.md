# i310D_assignment7

Your README should include:

The goal of your project:

- The goal of this project is to collect data from the internet and perform data cleaning, transformation, and visualization in order to extract insights and gain a better understanding of the dataset. Specifically, the project involves scraping data from the IMDB website to collect information about the top 1000 grossing movies, including features such as title, year, gross, votes, rating, and metascore.

Once the data has been collected and cleaned, the next step is to visualize the data using various tools and techniques to better understand the relationships between different variables. For example, the project will examine the relationship between metascore and gross or rating and gross to determine if there are any correlations.

Links to any relevant API documentation:

- Beautiful Soup Documentation: https://www.crummy.com/software/BeautifulSoup/bs4/doc/
- Build a web scraper with Python and Beautiful Soup: https://realpython.com/beautiful-soup-web-scraper-python/

The license of your data and any source data:

- MIT License
- Source data: IMDb movies https://www.imdb.com/list/ls098063263/

A data type and description for each attribute in your data:

- Data type for a collection of movies: list
- Data type for movie: dictionary
- Data type for rating: float
- Data type for votes: float
- Data type for metascore: float
- Data type for title: string
- Data type for year: int

Any known issues or potential issues, such as sources of bias in collection:

- Selection bias: The dataset only includes information about movies that are listed on IMDb, which may not accurately represent the full population of movies released. For example, independent films or movies that were not popular may be underrepresented in the dataset.

- User bias: IMDb is a user-generated platform, which means that the ratings and reviews in the dataset may be influenced by the preferences and biases of the users who submitted them. This could result in over-representation or under-representation of certain movies or genres.

- Data quality issues: The data in the IMDb dataset may contain errors, missing values, or inconsistencies that could affect the accuracy and reliability of any insights derived from it.
