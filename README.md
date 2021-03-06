# Parking Lot Activity
The following instructions pertain to running the Parking Lot serivce.

# Basic Information
- Programming Language Used: Python 3.8 (should work with Python 3.x)
- The output is shown in `stdout`.
- Installation step is optional (only to run the `pytest` command). The solution should work directly by running `main.py`. 
- A basic test is included to check whether the output matches the output as specified in the Activity Google Doc and Gist. 
- PEP8 Guidelines followed for code formatting and documenting.

# Assumptions Made
- There is only single entry and exit gate for the parking lot. 
- There is only one level/floor in the parking lot. 
- Assumptions specified in FAQ doc.

# Installation
`
pip install -r requirements.txt
`

# Usage
`
python main.py input.txt
`

# Code Improvements (Time Constraint)
- use of global variable `parking_lot` in `input_parser.py` can be handled better. 
- more robust tests can be written for the activity. 
- the methods inside `ParkingLot.py` can be fragmented and refactored to be clearer. 
- handling exceptions for incorrect and illegal commands. 
- structure the project in a more pythonic way.
