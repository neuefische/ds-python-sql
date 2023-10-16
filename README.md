# SQL in Python


![Mary Cassatt, In the Loge (1878), MFA Boston.](https://upload.wikimedia.org/wikipedia/commons/thumb/8/87/Mary_Stevenson_Cassatt_-_In_the_Loge_-_Google_Art_Project.jpg/540px-Mary_Stevenson_Cassatt_-_In_the_Loge_-_Google_Art_Project.jpg)

SQL is a very important language for working with data. People who can write both SQL and Python can work across a
broader spectrum in the data world. How does SQL
combine with python?

In this workshop we will be using Fugue and DuckDB and practice manipulating data using SQL.


### Start here:

🍴Fork this repo!

### Setup

Requirements:
- python > 3.10 but python <= 3.11.3
- As of October 2023, python 3.12 still doesn't support all the dependencies in the requirements, this can change later on.

If you use environments, do make a new environment and activated it. Then install the libraries:

macos/linux:

```python3 -m pip -r requirements.txt```

win:

```py -m pip install -r requirements.txt```

Alternatively you can create an account on [gitpod](https://www.gitpod.io) and use gitpod for the workshop.
- created a gitpod account (you can select github to authenticate)
- create new workspace and paste the link of this repo
- open ssh with token, install a python version with ```pyenv install 3.11.3``` and set the python version with ```pyenv global 3.11.3``` and install the libraries with ```pip install -r requirements.txt```
- open vscode from gitpod, and follow all the prompts (you need to have vscode installed locally). Alternatively, if you are a pycharm user, open that.

GITPOD!
Change the Python version (libraries don't yet work with 3.12): 
```sh 
pyenv install 3.11.3
pyenv global 3.11.3
```

### Problem:
 Our data science team needs features for predicting the customer life time value. The features they've asked for are recency, frequency and monetary value.

### Notebooks:
- [Intro-sql-in-python](Intro-sql-in-python.ipynb)
- [Intro-creating-tables](Intro-creating-tables.ipynb)
