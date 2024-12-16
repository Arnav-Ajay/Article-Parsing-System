# Article Parsing System for Neural Network Processing

A system for collecting articles and storing them in a database that will be compatible with neural network processing. 

The system uses JSON for article storage and SQLite as the database.

**Initial Source:** https://cointelegraph.com/  or  https://cointelegraph.com/rss

**Database Fields:**
- Title
- Author
- Publication date
- Article text
- Article URL
- Outbound links within the article
- Internal links (links to other articles on the same website)
- Tags

100% Python open source

Uses feedparser library to fetch the RSS feed from the website.

Json to store the articles and the metadata around it.

SQLite Database to keep track of the articles.


Creating a copy of the colab notebook will work for you. There will be changes if you want to use a different website, as this one is specifically for one.
