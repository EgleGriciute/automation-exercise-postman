# Automation Exercise Postman API Testing Project 🔔

## Project Overview
This repository contains a comprehensive Postman collection for API testing of the Automation Exercise website. The project aims to provide thorough API test coverage, ensuring the reliability and functionality of the website's backend services.

## Features
- Comprehensive API test collection
- Automated API testing scripts
- Environment-specific configurations
- Detailed test reporting
- CI/CD pipeline ready

## Prerequisites
- [Postman](https://www.postman.com/downloads/) (Latest Version)
- [Newman](https://www.npmjs.com/package/newman) (Optional, for CLI testing)
- Stable internet connection

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/EgleGriciute/automation-exercise-postman.git
cd automation-exercise-postman
```

### 2. Postman Import
1. Open Postman
2. Click "Import" 
3. Select the Postman Collection JSON file
4. Import Environment Variables

## Configuration
- Modify `environment` variables in Postman
- Update base URL if needed
- Configure authentication credentials

## Running Tests

### Postman GUI
1. Open Postman
2. Select the collection
3. Click "Run" to execute tests

### Newman (CLI)
```bash
# Install Newman globally
npm install -g newman

# Run collection
newman run automation-exercise-collection.json
```

## Test Coverage
- User Authentication
- Product Management
- Cart Operations
- Order Processing
- User Profile Management

##  Contributing
1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## Disclaimer
- Tests are based on Automation Exercise website API
- Ensure you have appropriate permissions
- Do not use for malicious purposes
