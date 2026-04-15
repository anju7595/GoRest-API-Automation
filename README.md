# GoRest API Automation Framework

This repository contains a professional API testing suite for the GoRest platform, demonstrating advanced Postman workflows and CLI-based execution for CI/CD readiness.

## 🚀 Overview
- **Tools:** Postman, Newman, Node.js
- **Reporting:** htmlextra
- **Automation Level:** 7+ Years SQA Expertise (Dynamic Data & State Management)

## 🛠️ Setup & Execution
1. **Install Node.js & Newman:**
   ```bash
   npm install -g newman
   npm install -g newman-reporter-htmlextra

2. Run the Suite:

newman run GoRest-Production.postman_collection.json -e Prod.postman_environment.json -r htmlextra

📊 **Key Features Implemented**

Dynamic Data: Pre-request scripts for unique email generation.

Stateful Testing: Environment variable chaining (POST -> GET -> DELETE).

Validation: Status code checks, data integrity, and schema validation.

CI/CD Ready: Headless execution via CLI for pipeline integration.
<img width="1774" height="867" alt="image" src="https://github.com/user-attachments/assets/d2bf79cf-d3b1-4704-a0a1-aaa1fd15c026" />
<img width="1856" height="874" alt="image" src="https://github.com/user-attachments/assets/ee904dbc-afa1-4c31-85b2-e29acadfe4e9" />

