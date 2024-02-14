YouTube Data Harvesting and Warehousing using SQL, MongoDB and Streamlit:

This project is built with streamlit, which allows users to collect and analyze data from youtube channels.
User can enter the channel id and collect the channels information such as videocount, likecount., by using google api.
Mongodb and sql are used to store and retrieve the mass data into the database. 

Tools used:
*Python
*Mongodb
*Postgresql
*Streamlit

Libraries used:
*Pandas
*Googleapiclient 
*Psycopg2
*pymongo

Approach:
1. By setting up Streamlit, it creates a simple UI where users can enter a YouTube channel ID, view the channel details, and select channels to migrate to the data warehouse 
2. To retrieve the channel and its video data, youtube api is needed. By using the Google API client library for Python it can make requests to the API.
3. After retrieving the data from the YouTube API, it can be stored in a MongoDB data lake by using the pymongo library to connect to mongodb. MongoDB is a great choice for a data lake because it can handle unstructured and semi-structured data easily.
4. After collecting data for multiple channels, it can be migrated to a SQL data warehouse. In this I used the PostgreSQL database and psycopg2 library to connect.
5. SQL queries are used to join the tables in the Postgresql data warehouse and retrieve data for specific channels based on user input.

