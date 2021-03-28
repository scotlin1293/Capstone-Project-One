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