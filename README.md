# Movies-ETL
Challenge 8 - ETL

He objective of the project is to gather data from both Wikipedia and Kaggle, combine them, and save them into a SQL database so that the hackathon participants have a nice, clean dataset to use. To do this, we will follow the ETL process: extract the Wikipedia and Kaggle data from their respective files, transform the datasets by cleaning them up and joining them together, and load the cleaned dataset into a SQL database.
The iterative process for cleaning data can be broken down as follows:

•	First, we need to inspect our data and identify a problem.
•	Once we've identified the problem, we need to make a plan and decide whether it is worth the time and effort to fix it.
•	Finally, we execute the repair.

Once we reached a unified database the objective of this challenge is to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. To achieve this objective we refactored the code from the module to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.
