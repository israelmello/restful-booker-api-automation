# Restful Booker API Automation

API automation testing project developed to demonstrate **QA Automation practices** using **Postman**, **Newman**, and **Continuous Integration with GitHub Actions**.

The main goal of this project is to validate the main workflows of the **Restful Booker API**, applying functional testing, contract validation, business rules validation, and automated execution through a CI/CD pipeline.

---

## 🚀 Technologies Used

- Postman
- Newman
- JavaScript
- REST API
- GitHub Actions
- Newman HTML Reporter
- Node.js
- Git/GitHub

---

# 📌 Automated Test Scenarios

## Authentication

### Create Token

Validations:

- Token creation flow
- Expected status code
- Response structure validation

---

## Booking

Automated flows:

- Create booking
- Get booking
- Update booking
- Delete booking

---

# ✅ Implemented Validations

The test suite includes different levels of validation:

## HTTP Validations

✔ Status Code  
✔ Response Time  
✔ Headers  
✔ Content-Type  

## API Contract Validation

✔ Required fields validation  
✔ JSON structure validation  
✔ Data type validation  

## Business Rules Validation

✔ Request vs Response comparison  
✔ Sent data validation  
✔ Returned data validation  

---

# ⚙️ Local Execution

## Install dependencies

```bash
npm install
```

## Run API tests

```bash
npm test
```

## Generate HTML report

```bash
npm run report
```

The generated report will be available at:

```
reports/report.html
```

---

# 🔄 CI/CD Pipeline

This project uses **GitHub Actions** to automatically execute API tests.

Pipeline workflow:

```
Push
 |
GitHub Actions
 |
Install dependencies
 |
Run Newman
 |
Execute API tests
 |
Generate HTML report
 |
Upload Artifact
```

---

# 📊 Test Evidence

The pipeline generates an HTML report containing:

- Executed requests
- Test results
- Response times
- Validation details

The report is stored as a GitHub Actions Artifact after each execution.

---

# 📂 Project Structure

```
restful-booker-api-automation/

├── .github/
│   └── workflows/
│       └── api-tests.yml

├── docs/

├── postman/
│   ├── collections/
│   └── environments/

├── reports/
│   └── report.html

├── package.json
└── README.md
```

---

# 🎯 Skills Demonstrated

This project demonstrates experience with:

- API Testing Automation
- Test Scenario Design
- HTTP Validation
- JavaScript for QA Automation
- Postman Collections
- Newman CLI Execution
- CI/CD Integration
- Automated Test Reporting

---

## Author

**Israel Mello**

QA Analyst | QA Automation

GitHub:
https://github.com/israelmello