**YouTube Data Harvesting and Warehousing using SQL, MongoDB and Streamlit:**

This project is built with streamlit, which allows users to collect and analyze data from youtube channels.
User can enter the channel id and collect the channels information such as videocount, likecount., by using google api.
Mongodb and sql are used to store and retrieve the mass data into the database. 

**Tools used:**
*Python
*Mongodb
*Postgresql
*Streamlit

**Approach:**
- Developed a YouTube data harvesting and warehousing project using SQL, MongoDB, and Streamlit
- Created a user-friendly interface using Streamlit to allow users to collect and analyze data from YouTube channels
- Implemented the use of Google API to retrieve channel information such as videocount and likecount based on user input
- Utilized MongoDB and SQL to store and retrieve large amounts of data in the database
- Used Python, Mongodb, Postgresql, and Streamlit as main tools for development
- Implemented key libraries such as Pandas, Googleapiclient, Psycopg2, and pymongo
- Set up a simple UI with Streamlit for users to input a YouTube channel ID, view channel details, and migrate selected channels to the data warehouse
- Integrated the Google API client library for Python to make requests to the YouTube API and retrieve channel and video data
- Stored the collected data in a MongoDB data lake using the pymongo library, as MongoDB is suitable for handling unstructured and semi-structured data
- Migrated the collected data to a PostgreSQL data warehouse using the psycopg2 library for connection
- Utilized SQL queries to join tables in the PostgreSQL data warehouse and retrieve data for specific channels based on user input.
