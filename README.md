## SRC

### Installing/Building Code

The code is in the Jupyter Notebook (.ipynb file format). It can be run locally using software such as Jupyter Labs or VSCode, or in the cloud using a service such as 
Google Colab.

### Usage of Code

The code requires the following Python libraries: pandas, requests, and vaderSentiment. These libraries must be installed locally for the code to run. This can be done
in Jupyter Notebook with the following command: !pip install [package_name]. To connect to the Reddit API certain credentials are required which are provided in the 
Jupyter Notebook file. The best practice would be to require a seperate config file for security, however we believe given the scope of this project providing the
credentials directly in the file is appropriate. The file will prompt the user for which subreddit they want to access and what types of posts they want to see. There
are options to download the data as a csv, to download the corresponding comments as a text file, and to print the results of the sentiment analysis.

## DATA

### Data Dictionary
| Variable | Description |
| -------- | ----------- |
| Title | Title of the subreddit post |
| ID | Reddit’s internal unique ID for each post |
| Number of Upvotes | Number of upvotes that the post received |
| Percent Upvoted | Ratio of the number of upvotes on post to the total number of upvotes and downvotes on post |
| Number of Comments | Number of comments on the post |
| Link | Link to article or image supplied |
| Upvote to Comment Ratio | Ratio of upvotes on the post to comments on it |
| Controversy Rating | Ratio of the upvote to comment ratio to the percent upvoted |
| Subreddit | Title of the subreddit that the post came from |

### Link to Data
[Our Data](https://github.com/jnm9aba/DS4002Project1/DATA)

### Notes
The controversy rating was a rating we came up with on our own that we believe will tell whether or not a post was controversial.

## FIGURES
| Figure | Takeaways |
| -------- | ----------- |
|  |  |
|  |  |
|  |  |
|  |  |
|  |  |
|  |  |
|  |  |
|  |  |
|  |  |

## REFERENCES
[1] I. Ivanova, “On Twitter, bad news spreads faster than good,” CBS News, 15-Jul-2021. [Online]. Available: https://www.cbsnews.com/news/twitter-bad-news-spreads-study/. [Accessed: 07-Sep-2022].

[2] J. Keeley, “The top 10 highest-rated reddit posts of All time,” MUO, 08-Nov-2021. [Online]. Available: https://www.makeuseof.com/tag/10-top-rated-reddit-posts-time/. [Accessed: 07-Sep-2022].

[3] “R/theoryofreddit - the 200 most active subreddits, categorized by content,” reddit. [Online]. Available: https://www.reddit.com/r/TheoryOfReddit/comments/1f7hqc/the_200_most_active_subreddits_categorized_by/. [Accessed: 14-Sep-2022].  

[4] “R/help - how is the percentage upvoted on the original post calculated, not the replies for the main post?,” reddit. [Online]. Available: https://www.reddit.com/r/help/comments/hz5n4c/how_is_the_percentage_upvoted_on_the_original/. [Accessed: 14-Sep-2022]. 

### Acknowledgements
We would like to acknowledge Professor Alonsi and Harsh for helping us throughout our project. The following Towards Data Science article also helped us implement
the VADER sentiment analysis library: [Article](https://towardsdatascience.com/the-most-favorable-pre-trained-sentiment-classifiers-in-python-9107c06442c6)

### MI1 Assignment
[Milestone 1](https://docs.google.com/document/d/1_9VuEV5jnkA3g263__p-ZIY3Z7F7dS8qcF2a_IcWDRI/edit?usp=sharing)

### MI2 Assignment
[Milestone 2](https://docs.google.com/document/d/1ZprHGB9gfskv4LiUauzqac8v8GBv4s8Hgy-vTTQr54c/edit?usp=sharing)

