# Restful Booker API Automation Testing Project

## Project Overview

This project demonstrates API regression testing automation using Postman and Newman on the Restful Booker application.

The objective was to automate the execution of previously designed API test cases, validate responses, verify business rules, and generate execution reports.

Note: Testing was performed against the public Restful Booker API environment. As the environment is shared and continuously updated, some results may vary between executions.


## Scope

The following API endpoints were tested:

* GET /booking
* GET /booking/{id}
* POST /booking
* PUT /booking/{id}

## Testing Activities

* API request execution
* Automated regression testing
* HTTP status code validation
* Response time validation
* JSON response verification
* Positive testing
* Negative testing
* Automated test reporting

## Tools Used

* Postman
* Newman
* Node.js
* GitHub
* JSON

## Key Results

* Automated execution of API test scenarios
* Validation of booking retrieval endpoints
* Validation of booking creation endpoint
* Verification of response structure and business data
* Generation of HTML execution reports

## Notable Findings

During testing, the following observations were made:

* An intentionally failing assertion was used to demonstrate Newman failure detection.
* A POST request with incomplete payload returned HTTP 500 Internal Server Error.
* A PUT request returned HTTP 403 Forbidden, indicating a possible authorization issue.

## Repository Structure

* Postman Collection
* Newman Reports
* Screenshots
* Documentation

## Author

Felicienne Miezan

QA Automation Portfolio Project
