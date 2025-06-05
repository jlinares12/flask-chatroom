# Flask Chat Room

This project was simply to get me started on understanding websockets and how they work. If you would like to see how I used the knowledge from this project to create my own project you can checkout it out [HERE](https://github.com/jlinares12/movie-night)

## To Run This Code

This program is designed to run locally. Assuming you already have python installed, to run this program on your machine first clone the repo.

    git clone https://github.com/jlinares12/flask-chatroom.git

Then change your working directory to "flask-chatroom" and then I recommend creating a virtual environment.

    $ cd flask-chatroom
    $ python -m venv venv

Once you have created your virtual environment, you have to activate the virtual environment using the following command.

    $ source venv/bin/activate

After activating your virtual environment install the necessary dependencies by running the following command.

    $ pip install -r requirements.txt

After installing the requirements you can now run the app.

    $ python3 run.py

Once you have the server running, your terminal will output something like this:

    * Serving Flask app 'run'
    * Debug mode: on
    WARNING: This is a development server. Do not use it in a production deployment. Use a production WSGI server instead.
    * Running on http://127.0.0.1:5000
    Press CTRL+C to quit
    * Restarting with stat
    * Debugger is active!
    * Debugger PIN: 118-955-816

Now you can open two tabs on your preferred web browser. Make sure to make one of your tabs a private tab.
Once you have both tabs open look at your terminal and find the where it says "* Running on". Copy that url and navigate to it on both browsers.
Now that you have both tabs open, on one tab write down a name and hit "create room". This will create a room with one person in it. At the top of your screen you will see a code. Copy that code, open your second tab and paste it in the input next to the "join room" button. After pasting the code, write a name down for this user and hit the "join room" button. Once you have both people joined you can now begin chatting with yourself.

Once you're done playing with the app you can go back to your terminal and hit "ctrl + c" on your keyboard to stop the server. You can then deactivate your virtual environment with the following command

    $ deactivate

Please note that you will have to activate your virtual environment again before running the server again.

Thank you for visiting my repo and a special thanks to Tech With Tim on youtube. If you want to see the video tutorial I followed hit this [link](https://www.youtube.com/watch?v=mkXdvs8H7TA&t=61s)