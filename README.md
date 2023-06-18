What have I programmed?

This code uses an API (newsapi.org) to get news articles and sources based on either a category or a query entered by the user as an argument. The API requires a unique key to access it, which is stored in the variable API_KEY.

The code defines three functions:

get_articles_by_category(category) - This function takes a category and returns a list of top articles from that category.
get_articles_by_query(query) - This function takes a query and returns a list of top articles related to that query.
get_sources_by_category(category) - This function takes a category and returns a list of sources that produce top articles from that category.
Finally, if the script is run directly, it gets the news articles from the category specified by the user as an argument, and then prints the title and url of each article. If the code is uncommented, it can also get news articles related to a specific query, or print the sources for a particular category.


Why did I build it?

I developed this code to address my challenge of finding specific computer science news articles while I was studying in college. By automating the search process, I was able to find relevant links quickly and avoid the time-consuming task of manually sifting through multiple sources. My passion for creating software solutions that solve practical problems motivated me to develop this code and continues to drive my interest in programming.
