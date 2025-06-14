# Automated Tests with Cypress 🚀

This project contains a comprehensive suite of automated end-to-end tests using **Cypress** to verify the functionality and reliability of the web application [automationpractice.pl](http://www.automationpractice.pl/index.php).

---

## 📊 Live Test Report

👉 **Latest report:** [mirgb.github.io/Cypress_automated_tests](https://mirgb.github.io/Cypress_automated_tests)

---

## 📝 Project Overview

This repository focuses on functional verification of critical user flows and UI elements to ensure stability and prevent regressions.

- **Testing Framework:** Cypress (v13.16.1)  
- **Test Type:** End-to-End (E2E) testing  
- **Base URL:** `http://www.automationpractice.pl/index.php`  
- **Test Scope:** Key user flows and UI functionality  
- **Viewport:** 1920x1080 (Full HD)  
- **Retries:** 1 retry in both run and open modes for better stability  
- **Security:** `chromeWebSecurity` disabled to allow cross-origin testing  

---

## ⚙️ Installation & Running Tests

To run tests locally:

1. **Prerequisites:** Install [Node.js](https://nodejs.org/).  
2. Clone the repository and open a terminal in the project root.  
3. Install dependencies:  
`npm install`
4. Open Cypress Test Runner (interactive mode):  
`npx cypress open`
5. Run tests headlessly and generate reports:  
`npm run report`

---

## 📊 Reporting

This project uses **Mochawesome** as the test reporter instead of Allure to showcase my knowledge of diverse reporting tools. In other projects, I usually use **Allure**.

- Reports are generated in JSON and HTML formats under `cypress/reports`.  
- Available scripts:  
- `npm run test` — run tests headlessly  
- `npm run report:merge` — merge Mochawesome JSON reports  
- `npm run report:generate` — generate HTML report from merged JSON  
- `npm run report` — full test and reporting workflow  

Check the live report here:  
👉 [https://mirgb.github.io/Cypress_automated_tests/](https://mirgb.github.io/Cypress_automated_tests/)

---

## ⚙️ Configuration Highlights

- `baseUrl` points to the target web application.  
- Retry enabled (1 retry) for stability.  
- `chromeWebSecurity` disabled for cross-origin testing.  
- Viewport set to 1920x1080.  
- Mochawesome configured for JSON and HTML output in `cypress/reports`.  

---

## 🎯 Why Mochawesome?

I chose **Mochawesome** here to demonstrate flexibility with different test reporting tools. While I typically use **Allure** in other projects, Mochawesome provides a clean, simple integration with Cypress and generates detailed reports in JSON and HTML formats, showcasing adaptability in test automation.
