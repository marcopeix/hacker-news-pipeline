# Hacker News Pipeline

This project introduces the field of data engineering by creating a data pipeline. Specifically, the data pipeline retrieves the 100 most populars keywords in the titles of articles in Hacker News. 

Each post has a set of keys. Here is a description of the most relevant keys:
* `created_at` - A timestamp of the story's creation time
* `created_at_i` - A unix epoch timestamp
* `url` - URL of the article's link
* `objectID` - Unique ID of the story
* `author` - The author's username on Hacker News
* `points` - The number of upvotes
* `title` - The title of the story
* `num_comments` - The number of comments for the article on Hacker News

**Objective:** To construct a data pipeline to retrieve the 100 most common keywords of the most popular articles on Hacker News.

**Techniques used:**
* Natural language processing
* JSON, datetime, data pipeline
* Function decorators
