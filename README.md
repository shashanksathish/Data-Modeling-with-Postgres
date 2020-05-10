# Summary of Project
Sparkify is a startup that wants to analyze the data they have been collecting on songs and user activity. The analytics team is keen in studying the songs that its users are listening to it. The company wants to develop a postgres database from the JSON. The core advantage of a database is the ease of using an ad-hoc queries.

# Design Schema 
The star network is created consisting of fact tables as songplays and the dimension table are users, artists, songs and time. The ETL pipelines fills up the postgres. The pandas is used to read the JSON file, the JSON file contains the data that has to be converted into postgres database.
