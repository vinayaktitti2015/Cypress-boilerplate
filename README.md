# Cypress with Cucumber BDD and AWS Amplify Console - CI/CD Pipeline

# Dependencies:
1. npm install
2. npm link
3. npm link cypress-cucumber-preprocessor

# Set host/ baseurl
1. go to cypress.json file
2. set baseurl

# Dashboard execution:
1. Go to project root, 
2. npx cypress open
3. click specific feature file [executionwillstart]

# Cmmd line execution:
1. npm run test:mochawesomereport
2. npm run test:allurereport
3. npm run generatereport

# Visual Test: 
We can cover visual testing with cypress using `cypress-image-snapshot` node_module
1. npm run test:visual-base
2. npm run test:visual-actual
3. Snapshots will be generated in 'snapshots' folder

# Reports:
1. Reports will be generated in 'mochawesomereport-report' folder - command line execution only
  
   ex: npm run test:mochawesomereport

2. Allure reports: 
    a. npm run test:allurereport
    b. npm run generatereport

# Reference
- [Detailed Article](https://medium.com/@vinayaktitti/getting-started-with-cypress-and-cucumber-api-2d7057e34047)


# Allure Reports:

![Screenshot](cypress/screenshots/allure.png?raw=true "Allure")

# Cucumber HTML Reports:

![Screenshot](cypress/screenshots/html1.png?raw=true "Cucumber HTML")
![Screenshot](cypress/screenshots/html2.png?raw=true "Cucumber HTML")

