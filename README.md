# Parabank-Cypress
**Installation**

Clone this repository: git@github.com:faraya-devsinc/Parabank-Cypress.git
Navigate to the project directory: cd your-repo-name
Install the project dependencies: npm install
Install Cypress: npm install cypress --save -dev
To configure cypress, execute: npx cypress open
To run cypress in headless mode: npx cypress run

**Usage**

To run all the tests in headless mode, run the following command: npm run test
To run a specific test file, run the following command: npm run test -- --spec "path/to/test/file.spec.js"
To open the Cypress Test Runner and run tests interactively, run the following command: npx cypress open

**Test Scripts**

The test scripts are located in the cypress/e2e directory. There are separate files for each feature that is being tested. The tests cover the following scenarios:

1. Register functionality
2. Login functionality
3. Verfication of Account Detaills both generic and specific
4. Verification of Tranfer Funds functionality
5. Verification of Loan Request functionality
