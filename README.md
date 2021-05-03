# hacker-news

![Hacker-News](https://user-images.githubusercontent.com/63714618/116851886-93ccb080-abf3-11eb-9366-d5c5a8c95ebf.jpg)


Hacker News is a site started by the startup incubator [Y Combinator](https://www.ycombinator.com), where user-submitted stories (known as "posts") are voted and commented upon, similar to reddit. Hacker News is extremely popular in technology and startup circles, and posts that make it to the top of Hacker News' listings can get hundreds of thousands of visitors as a result.

The original [data set](https://www.kaggle.com/hacker-news/hacker-news-posts) has almost 300,000 rows, but I will use one reduced to approximately 20,000 rows with all submissions that did not receive any comments removed, and then randomly sampling from the remaining submissions. Below are descriptions of the columns:

- *id*: The unique identifier from Hacker News for the post
- *title*: The title of the post
- *url*: The URL that the posts links to, if the post has a URL
- *num_points*: The number of points the post acquired, calculated as the total number of upvotes minus the total number of downvotes
- *num_comments*: The number of comments that were made on the post
- *author*: The username of the person who submitted the post
- *created_at*: The date and time at which the post was submitted


I am interested in posts whose titles begin with either **Ask HN** or **Show HN**. Users submit Ask HN posts to ask the Hacker News community a specific question.

Likewise, users submit Show HN posts to show the Hacker News community a project, product, or just generally something interesting. 

We'll compare these two types of posts to determine the following:

**Do Ask HN or Show HN receive more comments on average?**

**Do posts created at a certain time receive more comments on average?**
