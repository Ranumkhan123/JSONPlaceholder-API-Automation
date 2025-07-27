# JSONPlaceholder API – Postman Automation Portfolio Project

I explored real-world Postman skills on the widely used fake REST API: [JSONPlaceholder](https://jsonplaceholder.typicode.com/).

This repository highlights how to go beyond basic API testing by adding dynamic chaining, validations, data-driven testing, reporting, and CI/CD integration — all from scratch!

---

## Project Overview

This collection automates core API workflows on `/posts` and `/comments` endpoints, covering:
 
**Full CRUD Operations**  
**Chaining Requests Dynamically** (e.g., store POST ID → use in GET, PATCH, DELETE)  
**Data-driven Testing** with CSV  
**In-depth Validations** (status, time, body structure, types)  
**Newman CLI Automation** with HTML and htmlextra reports  
**GitHub Actions** for Continuous Integration (CI)  
**Postman Monitors** for scheduled runs

---


## 🛠 Tools & Technologies Used

| Tool              | Purpose                              |
|-------------------|--------------------------------------|
| Postman           | API testing + scripting              |
| JavaScript        | Pre-request + test logic             |
| Newman CLI        | Automation runner                    |
| newman-reporter-htmlextra | Beautiful HTML reports         |
| GitHub Actions    | CI for automated test execution      |
| CSV               | Input data for test iterations       |

---

## GitHub Actions CI/CD

`.github/workflows/postman-tests.yml` handles:

- Running tests with Newman
- Applying the right collection + environment
- Generating a fancy HTML report
- Uploading it as an artifact in the **Actions** tab

**Trigger:** Auto runs on every push to `main`

No more manual clicks — every commit validates your APIs!

---

##  How to Run

###  Using Postman Collection Runner
1. Import the collection and environment files
2. Click "Runner"
3. Select the collection, environment, and CSV file
4. Run all iterations and view logs + test results

---

##  Sample Report Screenshot

> You can embed an HTML report screenshot here for GitHub

---

##  Author

**Ranum Khan**  
[LinkedIn](https://linkedin.com/in/ranum-khan-qaengineer) | [GitHub](https://github.com/Ranumkhan123)  
Experienced QA Engineer with a strong foundation in manual and API testing, building automation-ready Postman collections and rich documentation.

---

##  License

This project uses public APIs and is intended for educational and portfolio purposes only.

