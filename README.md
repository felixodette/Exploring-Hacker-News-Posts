# Exploring-Hacker-News-Posts

Hacker News is a site started by the startup incubator Y Combinator, where user-submitted stories (known as "posts") are voted and commented upon, similar to reddit. Hacker News is extremely popular in technology and startup circles, and posts that make it to the top of Hacker News' listings can get hundreds of thousands of visitors as a result. In this project, we'll work with a data set of submissions to popular technology site Hacker News.
You can find the data set here, but note that it has been reduced from almost 300,000 rows to approximately 20,000 rows by removing all submissions that did not receive any comments, and then randomly sampling from the remaining submissions. Below are descriptions of the columns:
- id: The unique identifier from Hacker News for the post
- title: The title of the post
- url: The URL that the posts links to, if the post has a URL
- num_points: The number of points the post acquired, calculated as the total number of upvotes minus the total number of downvotes
- num_comments: The number of comments that were made on the post
- author: The username of the person who submitted the post
- created_at: The date and time at which the post was submitted

## Goal of the Project
Our project interested in analysing the posts with titles starting with:
- Ask HN: The posts for asking Hacker News community a specific question. Show HN: The posts for sharing with the community a project, product, or just generally something interesting. The goal of our project is to compare these two types of posts to study whether the number of comments and points (total number of upvotes) is influenced by:
- The type of posts — either Ask HN or Show HN? The submission time of the posts — what time?
