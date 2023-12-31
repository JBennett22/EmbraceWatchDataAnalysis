# EmbraceWatchDataAnalysis

Group Project that involves creating software for analyzing EmbraceWatch data. The Embrace Watch Data Analyzer is an application intended to take data from the Embrace Watch in the format of a csv to then process, graph, and analyze. View the manual file for more information. 


## Setup
Clone repo to desired location
`git clone https://github.com/JBennett22/EmbraceWatchDataAnalysis`

Command propmpt CD into repo directory
`cd EmbraceWatchDataAnalysis`

### Setup virtual environment
Windows: `python -m venv venv`

Unix-like: `python3 -m venv venv`

### Activate virtual environment

Windows: `.\venv\scripts\activate`

Unix-like: `source venv/bin/activate`

### Install required packages
`pip install -r requirements.txt`

## Executing
### Run main program
Windows: `python src\main.py`

Unix-like: `python3 src/main.py`

### Run data.py (basic test)
Windows: `python src\data.py`

Unix-like: `python3 src/data.py`


### Run data.py (quick test: Dataset dir, all subjects)
Windows: `python src\data.py -q` or `python src\data.py --quick`

Unix-like: `python3 src/data.py -q` or `python3 src/data.py --quick`


### Run displayapp.py (basic test)
Windows: `python src\displayapp.py`

Unix-like: `python3 src/displayapp.py`


### Run importwindow.py (basic test)
Windows: `python src\importwindow.py`

Unix-like: `python3 src/importwindow.py`


### Run describewindow.py (basic test)
Windows: `python src\describewindow.py.`

Unix-like: `python3 src/describewindow.py`
