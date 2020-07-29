# Sparkify
Repository for the Sparkify Capstone project that was part of the Udacity Data Scientist Nanodegree program

The goal of this project is to create a supervised machine learning model to predict the user's churn based on the user's previous interaction with the Sparkify music application. 

# Installations
This analysis was performed with the use of Jupyter Notebook and relies upon the following libraries:
 - pyspark
 - pandas
 - matplotlib
 - numpy
 
# Data
The data set was obtained as part of the Udacity Data Scientist Nanodegree program. the following are the data details:
- artist (string) - Artist Name
- auth (string) - Authorization (Cancelled, Guest, Logged In, Logged Out)
- firstName (string) - User's first name
- gender (string) - User's gender (null, F, M)
- itemInSession (long) - Item in Session
- lastName (string) - User's last name
- length (double) - Length of a session
- level (string) - User's account level (free, paid)
- location (string) - User's location
- method (string) - User's method (GET, PUT)
- page (string) - Page on which the user was (About, Add Friend, Add to Playlist, Cancel, Cancellation Confirmation, Downgrade, Error, Help, Home, Logout, NextSong, Roll Advert, Save Settings, Settings, Submit Downgrade, Submit Upgrade, Thumbs Down, Thumbs Up, Upgrade)
- registration (long) - registration id
- sessionId (long) - sessionId
- song (string) - name of the song being played
- status (long) - HTTP Status
- ts (long) - timestamp
- userAgent (string) - User's browser/platform information
- userId (string) - user's Id

# How to get started
The analysis is contained within the ``Sparkify.ipynb`` Jupyter notebook.

# Summary
Summary of the analysis is documented within the following medium blog post: 

# Acknowledgement
This analysis was performed as part of the Data Science Udacity Nanodegree.

