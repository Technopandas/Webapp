# Webapp

Idea is to develop api's that could be accessed by anyone just by registering their app with our portal, getting an access token and using our apis. 

We'll include web scraping api, supervised/unsupervised machine learning APIs and simple web apis like login, signup, etc. 

We'll give 3 ways to access our services:

1. ADHOC: Anyone can login, feed their data to our model, take the output and leave. the input and output files will remain in our systems till a specific period(eg: 7 days) and will be deleted once the period is over.

2. Cloud based: Anyone can login/register. User will get an access token for his application. Using this he can directly call our API, feed required parameters and generate output. User data resides on our servers, we take responsibility of user data.

3. On System: Users need to install an sdk of our product. APIs will be on our cloud. User will register their application and get an access token. Here, user will be responsible for his own data. Data won't be there on our servers. 

Input: It can be any structured/unstructured data. Ex. xyz.sql, abc.csv, ... 

Output: Visual graphs, reports, numerical scores. 

APIs: we'll code APIs for processing the data. For eg. If user wants to predict house rates in a particular area of a city, he'll give feed his data to our machine learning model. He can choose the model he wants. our API will give him his desired output in graphical format, report format and as numerical scores.

