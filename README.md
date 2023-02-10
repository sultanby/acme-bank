# acme-bank

## Project Overview

Acme Bank is a small credit union that provides assistance with deposits, loans, and a wide array of other financial services.  While the skeleton of their web app has been completed, there are certain vulnerabilities that were overlooked.

## Goals

 - Protecting it against Cross-Site Scripting (XSS) Attacks by using helmet, securing cookies, validating and normalizing data with express-validator, and implementing alternative methods to prevent DOM-Based XSS attacks.
 - Preventing SQL injection attacks by using prepared statements as well as validating input.
 - Preventing Cross-Site Request Forgery (CSRF) attacks by implementing csurf middleware and updating certain view pages to secure any cross-site request vulnerabilities.

 ## Setup

 After cloning the repo, navigate to project folder in terminal and `npm install` to install the project and after `node app` to start the server. Go to localhost:3000 in browser to explore the features. To open the .db file with a SQL browser to see the different tables containing user information and credit union records. A common application is DBBrowser. The database provided already has a number of users.
