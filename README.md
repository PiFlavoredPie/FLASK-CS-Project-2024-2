# FLASK-CS-Project-2024
 real CS project 2024 

Created 11-23-24. This project is my submission for the Advanced Computing Princeton Day School project. 
This project is a webbased secure communications channel that stores and distrobuted information based off inputs to (not very) securely connect information. 
Made to connect school clubs, forums, etc., with a secure background platform.

important files to check for code are as follows from this directory: 

mytester.py --> has a lot of the helper code and information 

flaskr/app.py --> a lot of the main routing functions, controls the whole site 

flaskr/templates/entry.html --> this is the main home page, controls the day information and the like 

flaskr/templates/results.html --> this is the template for the results page, also enter information to be encoded and the like 

flaskr/static/data --> this is where all of the data is stored, it is not ment to be human readable as it is fully encrypted. 
Each sheet is a separate category, each entry a different interest. 


Some other files are important for module routing and backend, but no one cares. 

anyway have fun, remember to run in a virtual environment with all the requirements lists in requirments.txt


make sure in the right directory to access app.py and run: 
flask --app app.py run --debug 

By default, it runs on port 5000


More information is in the specific function file and on the website's " How to Use " page. 

Information on each function is in the functions.txt file in this same folder

There is also some fun to be had with learning security and packet crafting with this website, explore and have fun.
