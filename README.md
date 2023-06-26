<h1 align="center">Hi 👋, I'm SATHISH KUMAR R</h1>
<p align="left"> <img src="https://komarev.com/ghpvc/?username=tirumal024&label=Profile%20views&color=0e75b6&style=flat" alt="tirumal024" /> </p>
<img align="right" alt="Coding" width="300" src="https://camo.githubusercontent.com/c1dcb74cc1c1835b1d716f5051499a2814c683c806b15f04b0eba492863703e9/68747470733a2f2f63646e2e6472696262626c652e636f6d2f75736572732f3733303730332f73637265656e73686f74732f363538313234332f6176656e746f2e676966">

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/https://www.linkedin.com/in/tirumal-s/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="https://www.linkedin.com/in/sathishkumarraj/" height="30" width="40" /></a>
<a href="https://www.instagram.com/rajendsathish_sk/?hl=en" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="mr.war_n_ing" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> </p>

# YouTube_Scrapping
# Introduction
This project is a YouTube API scrapper that allows users to retrieve and analyze data from YouTube channels. It utilizes the YouTube Data API to fetch information such as channel statistics, video details, comments, and more. The scrapper provides various functionalities to extract and process YouTube data for further analysis and insights.

# Features
The YouTube Data Scraper offers a range of features to help you extract and analyze data from YouTube. Some of the key features include:

`Retrieve channel statistics:` Get detailed information about YouTube channels, including subscriber count, view count, video count, and other relevant metrics.

`Fetch video details:` Extract data such as video title, description, duration, view count, like count, dislike count, and publish date for individual videos.

`Analyze comments:` Retrieve comments made on YouTube videos and perform analysis, such as sentiment analysis or comment sentiment distribution.

`Generate reports:` Generate reports and visualizations based on the collected data, allowing users to gain insights into channel performance, video engagement, and audience interaction.

`Data storage:` Store the collected YouTube data in a database for easy retrieval and future reference.

# Technologies Used
Python: The project is implemented using the Python programming language.

`YouTube Data API:` Utilizes the official YouTube Data API to interact with YouTube's platform and retrieve data.

`Streamlit:` The user interface and visualization are created using the Streamlit framework, providing a seamless and interactive experience.

`MongoDB:` The collected data can be stored in a MongoDB database for efficient data management and querying.

`PostgreSQL:` A powerful open-source relational database management system used to store and manage the retrieved data.

`PyMongo:` A Python library that enables interaction with MongoDB, a NoSQL database. It is used for storing and retrieving data from MongoDB in the YouTube Data Scraper.

`Psycopg2:` A PostgreSQL adapter for Python that allows seamless integration between Python and PostgreSQL. It enables the YouTube Data Scraper to connect to and interact with the PostgreSQL database.

`Pandas:` A powerful data manipulation and analysis library in Python. Pandas is used in the YouTube Data Scraper to handle and process data obtained from YouTube, providing functionalities such as data filtering, transformation, and aggregation.

pip install -r requirements.txt: To install the required dependencies.

# Process Flow
`Obtain YouTube API credentials:` Visit the Google Cloud Console.

Create a new project or select an existing project.

Enable the YouTube Data API v3 for your project.

Create API credentials for youtube API v3.

# ETL Process
Extracting Data from youtube API.

Transforming data into the required format.

Loading Data into SQL

# Application Flow
Select Data Retrieval and Processing Page from dropdown menu at the sidebar.

Input the Channel Id and click on Get Channel Statistics in order to retrive data from Youtube API.

Next click on Push to MongoDB to store data in MongoDB Lake.

Select a channel name from the dropdown Channel Details and click on Push to SQL to import data into PostgreSQL.

Once imported, you can select the Analysis and Reports Page from the drop down to get a detailed analysis of the collected data.

# Additional Information
Please note that when using this application, it is essential to comply with the YouTube Data API's terms of service and adhere to its usage limits to ensure uninterrupted access to the API. If you encounter any issues or have questions regarding the YouTube Data Scraper, please refer to the project's detailed documentation available in the GitHub repository.

# License
The YouTube Data Scraper is released under the MIT License. Feel free to modify and use the code according to the terms of the license.

# Conclusion
This YouTube API scrapper project aims to provide a powerful tool for retrieving, analyzing, and visualizing YouTube data, enabling users to gain valuable insights into channel performance, video engagement, and audience feedback.
