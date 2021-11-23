![Ekbana](/static/logo.png)
# Flask boiler plate project
The main aim of this repository is to act as a template for all the projects
created here at Ekbana. This ensures consistency as common formatters are pre-configured
and a pre-commit hooks file is added by default. This file makes sure that the code is well formatted before it is 
committed

## Instructions to install the boilerplate
Clone this repository in you local environment with the `git clone` command

### Install Requirements
This project requires python 3.6 or above installed on the local machine. 
Then you need to create a virtual environment and install requirements in it
- Create a virtual environment with python 3.6 or above
- Activate the virtual environment
- Install the requirements using the command `pip install -r requirements.txt` 

## Install the pre-commit
These commands ensure that the pre-commit script is executed each time 
before a user commits his/her code. 

Run these commands within the virtual environment:
```
pre-commit install
git add .pre-commit-config.yaml
``` 

Now the pre-commit script will check the project formatting when you attempt to commit your code.
Commit is approved only when the pre-commit script finds your code well formatted and documented.

Note: You can also run the pre-commit script without attempting to commit for test purposes.
Use the command below to run the pre-commit script manually.
```
pre-commit run --all-files
```
