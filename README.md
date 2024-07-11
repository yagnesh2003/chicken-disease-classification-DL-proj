## 1.Create a virtual environment :
Use this command in your command prompt to create a virtual environment. 
cmd : conda create -n DLenv python=3.8 -y

## 2.Create a template.py file : 

This file is used to automatically create a project structure. Instead of making the project structure everytime , 
we just need to run this file and it will automatically create project structure.

## 3.Install libraries and packages
Run this command to install all the neccessary libraries and packages in your virtual environment.
cmd : pip install -r requirements.txt

We will be using pre-built module "box.exceptions" for error handling.


## 4. Workflows 
Update config.yaml
Update secrets.yaml [Optional]
Update params.yaml
Update the entity
Update the configuration manager in src config
Update the components
Update the pipeline
Update the main.py
Update the dvc.yaml