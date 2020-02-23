#VotingApp
The app allows user to vote on different political parties. 


- To create a URLconf in the polls directory, create a file called urls.py
The next step is to point the root URLconf at the polls.urls module

-Database setup: 
By default, the configuration uses SQLite.
SQLite is included in Python, so you won’t need to install anything else to support your database.

-  USER, PASSWORD, and HOST must be added when using SQULite as a database

- Creating Models: In our poll app, we’ll create two models: Question and Choice. A Question has a question and a publication date. A Choice has two fields: the text of the choice and a vote tally.
