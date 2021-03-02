# Is My Online Post Likely to Receive A Response?

Social media is a popular method by which people create, share and/or exchange information and ideas on online networks. They come in many forms, from the photo sharing platform that is Instagram to the forum based platform that is Reddit.

## Interacting with Social Media
Social media platforms function in a variety of ways. Some involve uploading pictures and videos to an assigned profile, while others rely on community interaction. In this particular project, I will be analyzing data from the platform [Hacker News](https://news.ycombinator.com/). Hacker News is a technology and startup focused platform where user submit posts which can be voted on, and/or commented upon in the same vein as Reddit.

## Data set
The dataset is obtained from [Hacker news/Kaggle](https://www.kaggle.com/hacker-news/hacker-news-posts), and consists of a years worth of posts. Posts without comments were removed from the data set, and filtered to only include `Ask HN` or `Show HN` posts. `Ask HN` posts denote users asking the Hacker News community a question, while `Show HN` posts are users submitting either projects, products or any link to something they like to share. Overall, the data set contains about 20,000 rows of data.

### Features
**id**: The unique identifier from Hacker News for the post
**title**: The title of the post
**url**: The URL that the posts links to, if it the post has a URL
**num_points**: The number of points the post acquired, calculated as the total number of upvotes minus the total number of downvotes
**num_comments**: The number of comments that were made on the post
author: The username of the person who submitted the post
**created_at**: The date and time at which the post was submitted (Eastern time)


## Methodology
The aim of this study is to see which type of comments receive the most user responses on average. I am also interested in seeing when the best times to post are. I will achieve this by:

1.  Computing the total number of posts for each post type.
2.  For the post type with the most user engagement, segregate them based on the hour they were posted at

## Conclusions
Our results will provide insights into best times to post, as well as the type of posts most likely to receive a useful number of responses. The methodology outlined may be extended to analysis of data from other social media platforms.
