# query-scheduler
The project was about scheduling SQL queries stored in a googlesheet on MySQL workbench at a specified time.

The googlesheet stores all the SQL queries that need to be executed at a specified time during the day. The googlesheet API is used to pull the queries into the R console, a connection to MySQL workbench is established and the queries are executed one after the other.

The script is triggered to run at a specific time during the day using another script which acts as the scheduler.
