# Jupiter (Job Recommendation)
This website helps people optimize their job search. It can recommend new jobs based users history. 

# Modules
Gihub Job API Client: It is responsible for fetch jobs information from Github by using Github API. After user stored their favorite jobs, we can call MonkeyLearn API to extract keywords. Then it can recommend jobs according to those keywords.

RPC handlers: It communicates with users, Github Job API client and MySQL database directly. Users make requests and get responses from Rpc. 

MySQL databse: The data of users such as username and password, favorite jobs and recommend jobs will be stored in the MySQL database. I have used docker in the project as well. 
