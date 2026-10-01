# ExpenseTracker API Testing

## Overview
API testing of the Login and Register modules of an Expense Tracker application.

## Tools
Postman, Excel

## What is included
- Test cases (positive, negative, missing fields, duplicate email, wrong password)
- Postman collection with status code checks
- Bug reports
- Collection Runner result screensho

## Bugs found
- Register API accepts missing username/email (201 instead of 400)
- Register API allows duplicate email (201 instead of 409)
- Login returns generic "Bad credentials" when password is missing
- 500 error "Query did not return a unique result" for duplicate users

## How to use
1. Import the .json file in Postman
2. Create an environment with base_url = http://localhost:8081
3. Run the collection
