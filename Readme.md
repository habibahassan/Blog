## Amazing Blog
## Description
A personal blogging website where you can create and share your opinions and other users can read and comment on them
## Author and acknowledgement
 By Habiba Hassan
### Setup instruction
## Prerequisites
* python3.6
* pip
* Virtual environment(virtualenv)
* Flask-Mail
* PostgreSQL
## Cloning and running
Clone the application using git clone(this clones the app onto your device). In your terminal:

* $ git clone https://github.com/habibahassan/Blog.git

* $ cd pitch-project
## Creating the virtual environment
* $ python3.6 -m venv --without-pip virtual

* $ source virtual/bin/env

* $ curl https://bootstrap.pypa.io/get-pip.py | python
## Installing Flask and other Modules
* $ python3.6 -m pip install Flask

* $ python3.6 -m pip install Flask-Bootstrap

* $ python3.6 -m pip install Flask-Script

* $ python3.6 -m pip install Flask-Mail
## Testing the Application
To run the tests for the class files:

* $ python3.6 manage.py test
## Technologies Used
* Python 3.6
* Flask
## Behaviour driven development/ Specifications
* Behaviour	Input	Output
* Post pitch	Pitch is saved in a database	Post from database
* Comment on pitch	Leave a comment	Comment saved for display
* Upvote or downvote pitch	Click on like or dislike	Reflects on likes and dislikes
* Login and authenticate	Email address and password	Saved and used for authentication
## Support and contact information
Feel free to reach out to the developer at:
  *  Email:halimaadan92@gmail.com
## #  Licence
 licensed under the [MIT License](license)
 copyright(c) 2020 Blog
