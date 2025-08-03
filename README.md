# abarmin.pro
My personal blog, migrated from Wordpress

## Getting started

1. Install Python3: 

```sh
brew install python3
```

To make sure it is installed, execute: 

```sh
python3 --version
Python 3.13.5
```

2. Configure venv (if you haven't done it before for this env):

```sh
python3 -m venv venv
```

3. Enable venv: 

```sh
source venv/bin/activate
```

4. Install dependencies from `requirements.txt`: 

```sh
pip install -r requirements.txt
```

PS: if new dependencies are installed, don't forget to execute `pip freeze > requirements.txt` to update their versions. 

5. Run mkdocs: 

```sh
mkdocs serve
```

and next open `http://127.0.0.1:8000` in the browser to see the results. 

6. When all the changes are done, execute the following to build the site: 

```sh
mkdocs build
```