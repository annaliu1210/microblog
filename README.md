# twitter-blog
twitter-blog is a web application built under a backend Flask framework and frontend Bootstrap framework using a SQLite database.

The purpose of this application is to allow users to create tweets and interact with each other by following one another. Users can also create a profile page that includes the user’s tweets, following, followers, bio, and profile picture. 


## Setup Instructions
Clone the git repository:

    git clone https://github.com/annaliu1210/twitter-blog.git

Create a virtual environment and install the requirements:

    virtualenv venv
    source venv/bin/activate
    pip install -r requirements.txt

Create the database:

    flask db init
    flask db migrate -m "creating users and posts tables"
    flask db upgrade
    
Locally run the application by entering the following in the command line:

    flask run
