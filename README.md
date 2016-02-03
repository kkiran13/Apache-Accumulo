# Apache-Accumulo
Sentiment Analysis using Twitter Data

Task is to find popularity of NBA teams during a particular period.
Data is collected for NBA teams using Twitter API in python.
Based on wins and lose in tweets, sentiment of users is found which also gives popularity of teams.
Implemented in Apache Accumulo by creating 2 users EAST and WEST.

Running:
Create two users east and west in Accumulo.
Create table to store the result. Cell level security is applied by allowing East users to have access to 
Easter Conference teams and West users to have access to Wester Conference teams. 

Command used to run the jar:
bin/tool.sh /jarpath/accumulo_karthik.jar Main usrname pwd /inputpath tablename -u  username -p password
