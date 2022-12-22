# At the moment this is just a flask tutorial #

## Setup ##

In the root of the project, create a venv folder with:
```console
python -m venv venv
```
then activate the environment:<br>
(Windows)
```console
venv/Scripts/activate
```
(macOS)
```console
. venv/bin/activate
```
then install Flask:
```console
pip install Flask
```
To initialize the database:
```console
flask --app app init-db
```
To test:
```console
flask --app flaskr --debug run
```
