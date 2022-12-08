# Instagram-Crawlers

## Libarires used
Library       | Use
------------- | -------------
Instaloader   | This is a powerful and intuitive Python API for Instagram, it has some internally applied method and structure which helps to scrap data from an Instagram account, we can also customize the function according to our need.
pandas        | This library is used to manage the data in csv files which were formed during scraping details of any account.
Logging       | This library is used to print the output in some specific manner like for printing any information, we have used a function logger.info(“ ”), for printing any warning while giving any exception we had used logger.warning(“ ”)
time          | This library is used to give break between scraping to decrease the “Too Many Queries” error dur Instaloader library.
os            | This Library help us to get the access password and username which are present in .env file
json          | we store the some of the data like general details and counts file in .json file so to manage them we used json library
dotenv        | we add Python-dotenv to your application to make it load the configuration from a .env file


## Type of data scrap from and Instagram account 
If the account is public 
1. General Details (Username, User-Id, Number of Followers, Number of Following, Number of posts, Bio-data). 
2. Profile picture. 
3. Posts present in feed post by the owner of the account (All the images and videos).
4. text files of all the caption of all the corresponding post. 
5. .csv file of follower's username. 
6. .csv file of following's username.
7. List of the people like the post.
8. List of the people comment on the post. 
9. List of count of likes on each post. 
10. List of count of comments on each post.  
If the account is private 
1. General Details (Username, User-Id, Number of Followers, Number of Following, Number of posts, Bio-data). 
2. Profile picture. 

## how to use
1. Make a github clone using comment git clone comment
2. Create a .env file with your own username and password 
3. Put that file in same folder 

