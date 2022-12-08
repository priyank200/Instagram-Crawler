# Instagram-Crawlers

## Libarires used
*A.)Instaloader: - This is a powerful and intuitive Python API for Instagram, it has some internally applied method and structure which helps to scrap data from an Instagram account, we can also customize the function according to our need.* 
*B.) pandas: - This library is used to manage the data in csv files which were formed during scraping details of any account. 
*C.) Logging: - This library is used to print the output in some specific manner like for printing any information, we have used a function logger.info(“ ”), for printing any warning while giving any exception we had used logger.warning(“ ”)  
*D.) time: - This library is used to give break between scraping to decrease the “Too Many Queries” error dur Instaloader library. 
*E.) os: - This Library help us to get the access password and username which are present in .env file  
*F.) json: - we store the some of the data like general details and counts file in .json file so to manage them we used json library.  
*G.) dotenv: - we add Python-dotenv to your application to make it load the configuration from a .env file  

## Type of data scrap from and Instagram account 
If the account is public 
A.) General Details (Username, User-Id, Number of Followers, Number of Following, Number of posts, Bio-data). 
B.) Profile picture. 
C.) Posts present in feed post by the owner of the account (All the images and videos). 
D.) text files of all the caption of all the corresponding post. 
E.) .csv file of follower's username. 
F.) .csv file of following's username. 
G.) List of the people like the post. 
H.) List of the people comment on the post. 
I.) List of count of likes on each post. 
J.) List of count of comments on each post.  
If the account is private 
A.) General Details (Username, User-Id, Number of Followers, Number of Following, Number of posts, Bio-data). 
B.) Profile picture. 

## how to use
step 1: Make a github clone using comment git clone comment
step 2: Create a .env file with your own username and password 
step 3: Put that file in same folder 

