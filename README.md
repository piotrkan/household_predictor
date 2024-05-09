This is a repo for household occupancy prediction project. overall I have spent approx. 6 hrs on this project (6hrs spread across few days, not in a row). Work was done on Windows Machine on VSCode.

## Setup
~~~
#create a virtual env
python -m venv .venv_name 

#windows activation
.\.venv_name\Scripts\activate

#linux or mac activation
source ./.venv_name/bin/activate

#once activated, install dependencies
pip install -r requirements.txt

#install the venv as a kernel for the notebook
python -m ipykernel install --user --name=venv_name

#if you want to use jupyter notebook, run the following. I used VSCode for the development but jupyter notebook works just as fine
jupyter notebook
~~~

## Workflow

To examine the workflow, see main.ipynb. 

**NOTE: there is a data directory present but it's empty, this is because its not a good practice to share data on github. For the notebook to work correctly, move the data.db file to data folder**

## Comments

Working in notebooks is not my preferred way of working (I prefer working with scripts in IDE as it allows for better consistency, works better with version control and allows for unit testing and applying software development practices). However for the sake of this excercise, I have included everything in the notebook, including functions & classes I used for preprocessing and modelling. The notebook is divided in 3 sections and each section has their own dependencies imported.
