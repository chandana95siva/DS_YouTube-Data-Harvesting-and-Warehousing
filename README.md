# YouTube Data Harvesting and Warehousing
## Introduction:
This application is developed to extract, migrate, and query YouTube data using various technologies such as MongoDB, SQLite, and Streamlit. It provides functionalities to scrape data from YouTube channels, store it in a MongoDB database, migrate it to an SQLite database, and perform various queries on the stored data.
## Table of Contents:
Getting Started
Features
Dependencies
Usage
Contributing
License
contact
## Getting Started 
To get started with the application, follow these steps:
Clone the repository to your local machine: https://github.com/chandana95siva/DS_YouTube-Data-Harvesting-and-Warehousing.git
Install the required dependencies: pip install -r requirements.txt
Run the Streamlit application: streamlit run app.py
Access the application in your web browser at http://localhost:8501.
## Features
Data Extraction: Extracts channel details, playlist details, video details, and comment thread details from YouTube using the YouTube API.
Data Storage: Stores extracted data in a MongoDB database.
Data Migration: Migrates data from MongoDB to SQLite for further analysis.
Data Querying: Provides various queries to analyze YouTube data stored in the SQLite database.
User Interface: Uses Streamlit to create an interactive web interface for easy interaction with the application.
## Dependencies
The application is built using the following dependencies:

streamlit: For building the web application user interface.
googleapiclient: For interacting with the YouTube API.
pandas: For data manipulation and analysis.
pymongo: For interacting with MongoDB.
sqlite3: For interacting with SQLite databases.
## Usage
Extract Data: Enter the YouTube channel ID and click the "scrape" button to extract data. The extracted data will be stored in MongoDB.
Migrate Data: Select a channel from the dropdown list to migrate its data from MongoDB to SQLite.
Query Data: Choose from various predefined queries to analyze the YouTube data stored in the SQLite database.
## Contributing
Contributions to the project are welcome! To contribute, follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature/new-feature).
Make your changes and commit them (git commit -am 'Add new feature').
Push to the branch (git push origin feature/new-feature).
Create a new pull request.
## License
This project is licensed under the MIT License.
## contact
If you have any questions or suggestions regarding this project, feel free to reach out to me on:
📧 Email: sivachandana49230@gmail.com

🌐 LinkedIn: https://www.linkedin.com/in/chandana-s02/
