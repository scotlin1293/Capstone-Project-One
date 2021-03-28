Welcome to CineManiacs!

<a href="https://cinemaniacs.herokuapp.com/">View my demo!</a>

## About my project

* Search movies by title
* Select from categories including: upcoming, top rated, popular, and now playing.
* Contains information about the movies such as cast, revenue and recommendations.
* View the available trailers.
* Can create an account and log in, to enable features such as lists and reviews. 
* Add information to user profile.
* View other lists by other users. 


## Run a local version

1. You will need an API key from [The Movie Database API](https://developers.themoviedb.org/3) to run a local version.

2. Clone the repo.
 ```sh
git clone https://github.com/scotlin1293/Capstone-Project-One
```
3. Create a [virtual environment](https://docs.python.org/3/library/venv.html) in the directory (optional).
4. Install the requirements.
```sh
pip install -r requirements.txt
```
5. Create a database using [Postgres](https://www.postgresql.org/).
```sh
createdb capstone1
```
6. Create a new file named secrets.py and include the following.
```python
secret_key = "(whatever you would like the SECRET_KEY to be)"
api_key = "?api_key=(your TMDB API key)"
api_base = "http://api.themoviedb.org/3/"
```
7. Start flask server and go to [localhost:5000](http://localhost:5000)
```sh
flask run
```

## Built using

* Python
* HTML
* CSS
* Javascript
* [The Movie Database API](https://developers.themoviedb.org/3)
* [JQuery](https://jquery.com)
* [Axios](https://www.npmjs.com/package/axios)
* [Jinja](https://jinja.palletsprojects.com/en/2.11.x/)
* [Flask](https://flask.palletsprojects.com/en/1.1.x/)
* [Postgres](https://www.postgresql.org/)
* [SQL Alchemy](https://flask-sqlalchemy.palletsprojects.com/en/2.x/)
* [Flask-Bcrypt](https://flask-bcrypt.readthedocs.io/en/latest/)
* [WTForms](https://wtforms.readthedocs.io/en/2.3.x/)
* [Font Awesome](https://fontawesome.com/)
* [Balloon.css](https://kazzkiq.github.io/balloon.css/)
* [Muuri](https://muuri.dev/)
* [Web Animations](https://developer.mozilla.org/en-US/docs/Web/API/Web_Animations_API)
* [HammerJS](https://hammerjs.github.io/)