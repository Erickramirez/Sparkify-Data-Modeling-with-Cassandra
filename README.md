# Sparkify_Data-Modeling-with-Cassandra
Create an Apache Cassandra database which can create queries on song play data to answer the questions, and wish to bring you on the project.
In this project, It applies data modeling with Apache Cassandra and complete an ETL pipeline using Python.
Sparkify is a fictional popular digital media service created by Udacity, similar to Spotify or Pandora; many users use their services every day. It also has two modalities: using a free tier or a premium subscription model on which a user is free to upgrade, downgrade or cancel the service as they will like. It is important that the user likes the service to be loyal to Sparkify.

**the data modelling tasks are centered around three questions:**
1. Give me the artist, song title and song's length in the music app history that was heard > during sessionId = 338, and itemInSession = 4
2. Give me only the following: name of artist, song (sorted by itemInSession) and user (first and last name) for userid = 10, sessionid = 182
3. Give me every user name (first and last) in my music app history who listened to the song 'All Hands Against His Own'

### Prerequisites
The environment needed for this project:
1. [Python 3.6](https://www.python.org/downloads/release/python-360/)
2. [cassandra](https://cassandra.apache.org/)
4. [pandas](https://pandas.pydata.org/)

### Explanation of the files in the repository
1. Project_1B_Project_Template.ipynb: notebook file that contains all the process.
2. event_datafile_new.csv: concatenation of csv files in `event_data` folder files, it is denormalized data with the following structure:  ![image_event_datafile_new](/images/image_event_datafile_new.jpg "image_event_datafile_new")
3. images: folder that contains the images used in this file.
4. event_data: folder that contains the events of the user using Sparkify.
  
### Instructions to run the notebook
1. clone the github repository: `https://github.com/Erickramirez/Sparkify_Data-Modeling-with-Cassandra.git`
2. verify the Prerequisites
3. Open and run the file  file: Project_1B_ Project_Template.ipynb

