# Report On Web Application Security

## Content of the report:
- Testing methodologies on Web Applications
- What is DevSecOps
- Various SAST and DAST tools, differences between them
- How to Secure Web Applications Efficiently

## Practical Labs:
1. [https://portswigger.net/web-security/os-command-injection/lab-simple/](https://portswigger.net/web-security/os-command-injection/lab-simple/)
2. [https://portswigger.net/web-security/websockets/lab-manipulating-messages-to-exploit-vulnerabilities](https://portswigger.net/web-security/websockets/lab-manipulating-messages-to-exploit-vulnerabilities)

## Testing Methodologies on Web Applications:
There are various types of tests that are done on a web app before deploying it.

### 1. Functional Testing
This testing ensures that the application is functioning and all the requirements are met. This includes:
- **Unit Testing**: Testing each individual feature in the application
- **Integration Testing**: Checks the integrity of the application that everything works together.
- **System Testing**: This includes the testing of the whole system.
- **User Acceptance Testing (UAT)**: In this testing, the user checks the application as per their need.

### 2. Performance Testing
It’s done for checking the overall performance of the application.
- **Load Testing**: Testing the app under expected user load.
- **Stress Testing**: Testing the app under extreme load or conditions.
- **Scalability Testing**: Testing the application’s ability to scale.

### 3. Security Testing
Checking for vulnerabilities in the app.
- **Penetration Testing**: Performing attacks on the app to find vulnerabilities.
- **Risk Assessment**: Finding potential risks on the web app.

### 4. Usability Testing
Checking the user-friendliness of the app.
- **User Interface (UI) Testing**: Checking if the user interface is not too complex and looks attractive.
- **Accessibility Testing**: Checking if the application is accessible to all.

### 5. Compatibility Testing
Checking if the app is compatible with all required systems, devices, and browsers.
- **Browser Compatibility Testing**: Testing the app across various browsers.
- **Device Compatibility Testing**: Testing the app on various devices and systems.

### 6. Regression Testing
Checks whether the updated code does not affect the other functionality of the application.
- **Automated Regression Testing**: Testing by using automated bots or tools
- **Manual Regression Testing**: Testing the app manually to ensure everything works as expected.

## What is DevSecOps?

DevSecOps stands for Development, Security, and Operations. As we already know about DevOps, which is development and operation, integrating security ensures the safe development lifecycle. It’s a practice of integrating security at every stage of the software development process. It includes tools and processes that encourage collaboration between developers, security specialists, and operation teams to build software that is both efficient and secure.

## Various SAST and DAST tools, differences between them:
These are the two best approaches to test an application.

### 1. SAST (Static Application Security Testing) Tools
Static application security testing analyses the source of the program to find the vulnerabilities, not the same as dynamic testing. SAST is performed without executing the program. This method allows developers to find and fix vulnerabilities in the application at their early stages in the development cycle, before the software is deployed. 

Some common vulnerabilities are:
- SQL Injection
- Buffer Overflows
- XML external entity (XXE) attacks
- And other vulnerabilities from OWASP Top 10

#### SAST Testing Tools
Some Popular SAST tools are:
- **Klocwork** - It is a static code analyzer for C, C++, C#, Java, Javascript, and Python.
- **Checkmarx** – This tool supports multiple programming languages.

### 2. DAST (Dynamic Application Security Testing)
DAST scans running software applications in real-time against live vulnerability sources to find security flaws and vulnerabilities. While SAST scans the application’s source code before it’s deployed, DAST tests the running application and has no access to the source code of the application. 

Since DAST has no visibility of the source code, it simulates an outside attacker’s perspective. It tries out all the application’s functions. It can detect security vulnerabilities that SAST cannot because some vulnerabilities only appear when the program is running. It can also test APIs, web services, and detect misconfigurations in servers or databases.

#### DAST Testing Tools
Most of the DAST testing tools out there are commercial and aren’t open-sourced, but there’s still one tool that is open-sourced and that is:
- **Arachni** – It provides a rich functionality while being open-sourced and it’s based on the Ruby framework, which supports scanning web applications for vulnerabilities like:
  - XSS (with DOM variants)
  - SQL injection
  - NoSQL injection
  - Code injection
  - File inclusion variants
  - Etc.

#### Conclusion of Difference:
Actually, SAST and DAST are both crucial for testing software, and combining both SAST and DAST offers a stronger approach to security testing at different stages of development.

## How to Secure Web Applications Efficiently
The various practices to secure web apps are:

### 1. Secure Coding Practices
- **Input Validation**: Sanitizing user inputs to prevent injection attacks.
- **Use Parameterized Queries**: Prevent SQL injection by using parameterized queries instead of dynamic SQL.
- **Secure Authentication**: Implement strong authentication mechanisms, like (MFA).

### 2. Regular Updates and Patching
- **Keep Software Up to Date**: Regularly update and patch your software, frameworks, and libraries to fix vulnerabilities.
- **Third Party Dependencies**: Taking regular checks and updating third-party dependencies to ensure they are free of vulnerabilities.

### 3. Encrypt Data
- **Transport Layer Security (TLS)**: Using TLS to encrypt data transmissions between client and server.
- **Encrypt Sensitive Data**: Encrypting sensitive data stored in databases and other storage mediums.

### 4. Implement Security Headers
- **HTTP Security Headers**: Use headers like Content Security Policy (CSP), Strict-Transport-Security (HSTS), and X-Content-Type-Options to mitigate various security risks.

### 5. Regular Security Testing
- **Static and Dynamic Analysis**: Use SAST and DAST to find vulnerabilities in the application’s code or while running.
- **Penetration Testing**: Doing penetration testing to simulate real-life attacks to find vulnerabilities.

### 6. Secure Configuration
- **Least Privilege**: Follow the principle of least privilege for accessing databases, APIs, and other resources.
- **Environment Hardening**: Disable unnecessary services, ports, and features in your environment to reduce the attack surface.

### 7. Secure APIs
- **Authentication and Authorization**: Implement strong authentication and authorization mechanisms for APIs.
- **Rate Limiting**: Use rate limiting to prevent denial-of-service attacks.

### 8. Monitor and Respond
- **Logging and Monitoring**: Monitoring the logging information to detect and respond to security threats.
- **Incident Response Plan**: Develop a well-defined incident response plan to minimize the attack and security breaches while securing the data.

## LAB - 1
Status – completed

## LAB - 2
Status – completed
