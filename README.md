# <img src="https://i.ibb.co/0Fn1Ysb/pydood.jpg" alt="Python Doodle" width="20" height="20"> Fun Fact Generator <img src="https://i.ibb.co/0Fn1Ysb/pydood.jpg" alt="Python Doodle" width="20" height="20">

## Description :- 

This project shows how a flask app is created and being run. 

This simply just changes the content which is the fact upon each refresh.

## Run Locally :-

This project is initiated by uv instead of pip (cause i'm just dyslexic). You can delete the `pyproject.toml` and `uv.lock` safely. Or just be cruel to your storage (just like me).

### Using Docker (Recommended) :-

Get the code in your local machine
```
git clone -b fun-fact-generator --single-branch https://github.com/ethicks-x/Py-Proj.git

```
get into the code folder

```
cd Py-Proj
```

Build the Dockerfile

```
docker build -t fun-fact:latest .
```

Start the container

```
docker run -p 5000:5000 fun-fact:latest
```

Check on your browser `localhost:5000`

### Locally (Linux):- 

Get the code in your local machine
```
git clone -b fun-fact-generator --single-branch https://github.com/ethicks-x/Py-Proj.git

```

Get into the code folder

```
cd Py-Proj
```

Fire up a virtual environment
```
python3 -m .venv
source .venv/bin/activate
```

Install dependencies
```
pip install -r requirements.txt
```

Start the app
```
python3 app.py
```

## Contact :-
sinchangayen@gmail.com
