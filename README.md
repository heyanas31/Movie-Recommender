# Movie-Recommender

# Overview:
This project implements a movie recommendation system using the K-Nearest Neighbors (KNN) algorithm. The system recommends similar movies based on content features like genres, keywords, cast, and crew. The implementation of this project has done in Python with data preprocessing and model training techniques.

# Key Features:
The main features that this project include are the following:
•	Reading metadata using pandas
•	Pre-Processing of movie metadata
•	KNN algorithm with cosine similarity
•	TF-IDF vectorization of movie tags
•	Visualization of recommendation results
•	File-based input/output handling

# Working:
The application is design to provide movie recommendations through a simple user interface. It take movie name from user and recommend movies based upon the user input movie by visualizing the genres, cast and crew. It applies the KNN algorithms with cosine similarity in order to find similar movies for recommendation. Here is the working in detail:
User Authentication:
 When user visits the application, they need to log in using a username and password. This helps keep things secure and make sure that only authorized users can access the system. 
Movie Input:
After logging in the users can type in the name of any movie according to their interest. This system takes that movie name and uses it to look for a related list of recommended movies. It also saves the movie name temporarily in a text file for tracking purposes.
Recommendation Display:
Once the movie name is submit, the system apply machine learning algorithms and techniques in order to check related movies. If related movies found it will store them into the movie recommendation file. Then it reads the movie recommendations and display them on the screen. But if there’s no file available for that movie, the system display the user that there are no suggestions for this movie. 
Watch Later:
The app gives users the option to select any of the recommended movies they like and save them to a personal “Watch Later” list. This list has written to a file so they can keep track of movies they want to watch in the future. It is a handy feature for building a personal movie queue.
Logout:
When user is done, they can click on the logout button. This will ends their session and brings them back to the login page. It is a simple way to make sure user accounts stay private and secure.

Tools and Techniques:
Python:
The system is using Python, which provides simplicity to the system. Python makes it easy to handle file operations and to apply Ml algorithms.
Flask:
Flask is use as the core web framework. In this system, the purpose of using flask is to provide functionality to the front end. 
File handing:
File handling has been use efficiently in this system in order to store user movie recommendations data in the text file, which make it simple and easy to fetch that data to display to the user.
KNN:
KNN has been use to find movies that are similar to a given movie by comparing feature vectors (like genres, tags, or user ratings). It works by measuring the distance between the input movie and others in the dataset and selecting the ‘k’ most similar ones to recommend.
Matplot-lib:
In this system, it is use to plot graphs to show things like the accuracy of the recommendation system and similarities between movies. It make it easier to analyze patterns and present findings.
