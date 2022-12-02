# Predict Customer Churn

- Project **Predict Customer Churn** of ML DevOps Engineer Nanodegree Udacity

## Project Description
This project We created a library based on given churn_notebook.ipynb file. We apply tests and refactored the given code according to clean code principals.

## Files and data description
* File 1: churn_library.py
  The churn_library.py is a library of functions to find customers who are likely to churn.
* File 2: churn_script_logging_and_tests.py
    Contain unit tests for the churn_library.py functions.
  


## Running Files
* Run: Running the Test file churn_script_logging_and_tests.py Bellow command could be executed. It will user the library churn_library.py.

When we use bellow command We will get code rating like 
    `pylint churn_library.py`
    `Your code has been rated at 8.00/10 (previous run: 7.20/10, +0.80)`
    
    and 
     `pylint churn_script_logging_and_tests.py `
     `Your code has been rated at 8.00/10 (previous run: 7.80/10, +0.20) `
     
Using following comand we can do some auto formating to our code
`autopep8 --in-place --aggressive --aggressive churn_script_logging_and_tests.py
autopep8 --in-place --aggressive --aggressive churn_library.py`

After formating witj PEP 8 Style we can see the optimised result for our coding ratings

 `pylint churn_library.py`
    `Your code has been rated at 8.47/10 (previous run: 8.00/10, +0.47)`
    
    and 
     `pylint churn_script_logging_and_tests.py `
     `Your code has been rated at 9.25/10 (previous run: 8.00/10, +1.25) `
     
    






