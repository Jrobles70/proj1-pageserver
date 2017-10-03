# Project 1 Page Server

This project uses python to create a simple webserver that hosts specific html pages

## Prerequisites

* Python 3 
* a credentials.ini file locatated in the pageserver folder

### Getting Started

Create a credentials.ini and paste in these lines filling in the appropriate information

```
[DEFAULT]  
author= Justin Robles
repo=https://github.com/Jrobles70/proj1-pageserver
PORT = 5000
DOCROOT = pages
```

## How To

### Command Line
Use the command line to set a specific port

```
python3 pageserver.py -P 8889
```
Navigate to you port using

```
localhost:PORTNUMBERHERE
```


## Authors

* **Justin Robles** - Jrobles@uoregon.edu

