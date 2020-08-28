template-project
==============================

Lorem ipsum etc etc

| Author 	| Benjamin Jones 	|
|--------	|----------------	|
| Date   	| XX/XX/2020     	|


### Getting Started 


Got _docker?_ You can run the notebooks by running the following command from this root directory

```docker build -t yourusername/template-python-project . ```
 
followed by

```docker run -p 8888:8888 yourusername/template-python-project```

_Else_, to generate the environment, call ```tox -e develop``` from the terminal/command line in the project directory from a python 3.7 environment with ```tox``` installed. This creates a project specific virtual environment and installs the relevant packages. 

Once complete, activate the virtual environment with ```.\.venv\Scripts\activate``` on Windows or ```source .venv/bin/activate``` on a Mac. 

(Alternatively, calling ```pip install -r requirements.txt``` followed by ```python setup.py develop``` in a relevant virtual environment is sufficient).


### Overview

@btjones-me



<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>

