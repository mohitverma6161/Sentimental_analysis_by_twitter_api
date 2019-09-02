# Sentimental_analysis_by_twitter_api                                                                                                     
This is a basic program for the sentimenatal analysis.                                                                                     
To make your own sentimental analysis, do the following steps:                                                                             

i)Make your twitter account                                                                                                               
ii)Go to https://developer.twitter.com/en/apps and log in with your Twitter user account.                                                 
iii)Click “Create an app”                                                                                                                 
iv)Fill out the form, and click “Create”                                                                                                   
v)A pop up window will appear for reviewing Developer Terms. Click the “Create” button again.                                             
vi)In the next page, click on “Keys and Access Tokens” tab, and copy your “API key” and “API secret” from the Consumer API keys section.   
vii)Scroll down to Access token & access token secret section and click “Create”. Then copy your “Access token” and “Access token secret”.                                                                                                                                              

Now open jupyter and copy code present in the file above.                                                                                 
In the consumer_key,consumer_secret,access_token,access_token_secret fill your own values that you copied above.                           
                                                                                                                                           
Now in "public_tweets = api.search("Modi")"->In this line instead of Modi,you can put any value like Shah,Jaitley,etc.                     
After the sentimental analysis you can see two property for every twitt i.e. polarity and subjectivity.                                   
                                                                                                                                           
polarity->Polarity is float which lies in the range of [-1,1] where 1 means positive statement and -1 means a negative statement.         
subjectivity->ubjective sentences generally refer to personal opinion, emotion or judgment whereas objective refers to factual              information. Subjectivity is also a float which lies in the range of [0,1].                                                                

Please avoid any grammatical error.
