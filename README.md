This is a web application built with Python and Flask that implements a face recognition-based attendance system. 
The system allows users to register their faces, mark attendance using face recognition, and view attendance records.

**Features**

User Registration: Users can register their faces by providing their name and ID. The application captures multiple images 
of the user's face through the webcam and stores them in a designated folder.

Face Detection and Recognition: The system utilizes OpenCV's Haar cascade classifier for face detection and 
a K-Nearest Neighbors (KNN) classifier trained on the registered user data for face recognition.

Attendance Marking: When a registered user's face is detected and recognized, 
the system automatically marks their attendance with the current date, time, and user details in a CSV file.

Attendance Records: The home page displays a table with the attendance records for the current date, 
including the user's name, ID, and attendance time.

User-friendly Interface: The application provides a user-friendly web interface built with 
HTML, CSS, and Bootstrap for easy navigation and interaction.

**Technologies Used**

Python
Flask (Web Framework)
OpenCV (Computer Vision Library)
scikit-learn (Machine Learning Library)
NumPy (Numerical Computing Library)
pandas (Data Manipulation Library)

**Getting Started**

Clone the repository
Install the required dependencies
Run the Flask application
Access the web interface through the provided URL

**Usage**

Register new users by providing their name and ID
Start the face recognition process to mark attendance
View the attendance records for the current date on the home page

**Acknowledgments**

OpenCV
scikit-learn
NumPy
pandas
Flask
