The NEWS API should be used as data source


To get category wise news use the following end point. [Category News endpoint]
(https://newsapi.org/v2/top-headlines?category=<<news_category>>&apikey=<<api_key>>&page=1)
To get trending news use the following endpoint. [Top Headlines endpoint]
(https://newsapi.org/v2/top-headlines?country=in&apikey=<<api_key>>&page=1)
To search for any news based on serach text . [News search endpoint]
(https://newsapi.org/v2/everything?q=<<search_text>>&apiKey=<<api_key>>&language=en&page=1)


To register for an API key, follow these steps:


You need to signup to [NEWSAPI] (https://newsapi.org/register).
After registration, API key is generated for you.


Assignment:

As a user I should be able to get all the News from the api.
As a user I should be able to filter the Inportant parts of a news.
As a Developer I should be able to store todays News into the db.json.
As a user I should be able to search the news based on the title.
