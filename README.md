# webscraping
This code is a web scraper application built using Python's tkinter library for GUI and BeautifulSoup for web scraping. The application allows the user to scrape product information from websites such as ebay, amazon, and jumia. The user inputs a keyword and selects the website to scrape from. The information retrieved from the website is displayed in the GUI window of the application. The application also has a menu bar with options such as "File," "Help," "Contact us," and "Guide." The "Help" option opens a window with help topics, and the "Contact us" option opens a window with contact information. The data retrieved from the website is saved in a list of dictionaries with keys as "description," "price," and "link."
### project preq

This project requires good knowledge of python and the Tkinter library. 
tkinter is module that is frequently used to build graphical interface in many language GUI.

and we will need also "bs4" and "Requests" modules.

```
python -m pip install pillow
```

## Requirements

```
Tkinter==8.6
bs4==4.11.1
Requests==2.28.1
```

## and for you benefice, use a virtual environement :

### creating a venv for windows\Linux\Mac :

```
python -m venv <directory>
```
### activating venv 

for Windows :

```
# cmd
venv\scripts\activate.bat
# powershell 
venv\scripts\Activate.ps1
```

for Linux\Mac :

```
source myvenv/bin/activate
```

### what's inside a venv?

for windows :

```
.
├── Include
├── Lib
│   └── site-packages
├── pyvenv.cfg
└── Scripts
    ├── activate
    ├── activate.bat
    ├── Activate.ps1
    ├── deactivate.bat
    ├── pip3.10.exe
    ├── pip3.exe
    ├── pip.exe
    ├── python.exe
    └── python.exe
````
for Linux\Mac:
```
.
|--bin
|   |--activate
|   |--activate.csh
|   |--activate.fish
|   |--easy_install
|   |--easy_install-3.7
|   |--pip
|   |--pip3
|   |--pip3.7
|   |--python->python3
|   |--python3->/usr/local/bin/python3
|
|--include
|--lib
|   |--python3.7
|         |--site-packages
|--pyvenv.cfg
```

### deactivating a venv

Once you have finished working on your project, it’s a good habit to deactivate its venv. By deactivating, you leave the virtual environment. Without deactivating your venv, all other Python code you execute, even if it is outside your project directory, will also run inside the venv.

```
deactivate
```


uninstall all package 
````
pip freeze | xargs pip uninstall -y
````

## the package that i created is Fatalscraper 0.0.1 

to run the project , you need to install all the pre-requis of the project , I just mention it on the requirements file . so you need to install them all .
then run to python interpreter or a python file and tap this code :
```
from mypackage import main
```
then run the file.
