# [Flaskr](http://flaskr.fly.dev)</h1>

![passing](https://img.shields.io/badge/build-passing-success)

## About

Flaskr is a Tumblr style blog application, from the [official Flask tutorial](https://flask.palletsprojects.com/en/2.2.x/tutorial/). You can view posts from other users, or make, edit and delete your own posts. Feel free to leave a post! (But maybe keep it family friendly :upside_down_face:)

## How to use

If you're just interested in playing around with the Flaskr app, you can do so [here](http://flaskr.fly.dev/).

If you're interested in working with the code, simply clone the repository, navigate to the folder containing the app, and enter the following into the terminal:

#### For windows

```
> py -3 -m venv venv
> venv\scripts\activate
> pip3 install -r requirements.txt
```

#### For macOS/Linux

```
$ python3 -m venv venv
$ . venv/bin/avtivate
$ pip3 install -r requirements.txt
```

This will create and activate the virtual environment, then install the dependancies. To run the app locally, enter the following:

```
$ flask --app flaskr --debug run
```

You can find the app, and any changes you make, by opening your browser to http://127.0.0.1:5000/
