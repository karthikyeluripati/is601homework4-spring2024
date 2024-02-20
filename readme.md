# Homework 4

## Advanced Calculator with Faker and Command Line

# Project Install Instructions

## Install 
1. Clone
2. pip install -r requirements.txt

## Testing
1. pytest
2. pytest --pylint
3. pytest --pylint --cov

## Following points are covered
1. Add the "faker" libary with the command "pip install faker" and then do a pip freeze > requirements.txt.(FAKER)
2. Add a new command to pytest to generate N number of records, so that you can run the following command: pytest --num_records=100 to generate 100 records. The code to do this is in the tests/conftest.py file.(TEST DATA GENERATION)
3. Add a main.py file to serve as an entry point to your program and add the code from my main.py, so that you can have some exception handling to your program.(USER INPUT)
