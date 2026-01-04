# API Testing Framework – Postman & Newman

## Overview
This project demonstrates API testing using Postman collections executed via Newman (CLI).
It is designed to be CI/CD friendly and uses environment variables for configuration.

## Tools & Technologies
- Postman
- Newman
- Node.js
- REST APIs
- Linux CLI

## Project Structure
- Postman Collection: `ReqRes API Testing.postman_collection.json`
- Environment File: `Local-API-Env.postman_environment.json`

## How to Run Tests
1. Install dependencies:
   ```bash
   npm install -g newman

2. Run the collection:
   ```bash
  newman run "ReqRes API Testing.postman_collection.json" \
  -e "Local-API-Env.postman_environment.json"

##Key Concepts Covered
- Environment-based configuration
- CLI-based API execution
- Handling public API limitations
- Debugging API failures

##Author
 Dipanshi   
