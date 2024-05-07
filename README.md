#################Project Structre##################################################
EcoEye-Online_Bird_Monitoring_System
|
|-- App
|   |-- Templates
|   |   |-- app
|   |       |-- Static
|   |           |-- css
|   |           |-- img
|   |           |-- js
|   |           |-- lib
|   |
|   |-- Migrations
|   |-- Admin.py
|   |-- Apps.py
|   |-- Models.py
|   |-- Tests.py
|   |-- Urls.py
|   |-- Views.py
|
|-- Ecobird
|   |-- __init__.py
|   |-- asgi.py
|   |-- settings.py
|   |-- urls.py
|   |-- views.py
|   |-- wsgi.py
|
|-- manage.py
|-- model.h5
|-- module.py
|-- requirement.txt
###################################################################################
1. Download zip file from Eco_Eye repo
2. Then Unzip it
###################################################################################
#################Then Create Virtaul environment in VS code#######################
1. First create folder in local disk such as C: and open folder in VS code
2. Then open terminal
3. python -m venv project_path\venv
   Look folders created under project
4. Press cnt+shif+p look for python interpretor in search box > click on find>
   Then go to same project path and go to scripts and then select python
   Or either use this command 
   .\venv\Scripts\activate
5. python -m pip install --upgrade pip
6. pip install -r requirements.txt
###################################################################################
######################To install Library outside of requirement.txt################
pip install library_name
###################################################################################
######################Command to run project#######################################
1. Command to run project locally 
python manage.py runserver
###################################################################################
