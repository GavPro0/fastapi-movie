# fastapi-movie [main]

## Create and Activate VirtualEnv
```sh
# Create Python VirtualEnv. 
python3 -m venv env_movie

# Activate VirtualEnv in Linux.
source env_movie/bin/activate

# Deactivate VirtualEnv.
deactivate

```

## Install Python Requirements
```sh
# Pip Upgrade.
python -m pip install --upgrade pip
python3 -m pip install --upgrade pip

# Install Libs.
pip install fastapi
pip3 install fastapi

pip install uvicorn
pip3 install uvicorn

```

## Test FastAPI with Local Host
```sh
# Run FastAPI code. 
uvicorn main:app

# Test in Web Browser.
http://127.0.0.1:8000

```

## Test FastAPI with Local Network
```sh
# Run FastAPI code, reload changes, set port and enable network. 
uvicorn main:app --reload --port 5000 --host 0.0.0.0

# Docs and Tests with Swagger.
http://127.0.0.1:5000/docs
http://127.0.0.1:5000/docs#/default/message__get
http://127.0.0.1:5000/docs#/movies/get_movies_movies_get
http://127.0.0.1:5000/docs#/movies/get_movie_movies__id__get

# Test in Web Browser.
http://127.0.0.1:5000
http://127.0.0.1:5000/movies
http://127.0.0.1:5000/movies/1
http://127.0.0.1:5000/movies/2

```

