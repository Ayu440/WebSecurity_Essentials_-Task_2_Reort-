# WebSecurity_Essentials_-Task_2_Reort-
All you need to know about how to make a web application secure and test it.
Report On Web Application Security

Content of the report:

Testing methodologies on Web Applications

What is DevSecOps

Various SAST and DAST tools, differences between them

How to Secure Web Applications Efficiently

Practical Labs:

OS Command Injection Lab - PortSwigger

WebSockets Lab - Manipulating Messages to Exploit Vulnerabilities - PortSwigger

Testing Methodologies on Web Applications:

There are various types of tests that are done on a web app before deploying it:

1. Functional Testing

This testing ensures that the application is functioning, and all the requirements are met. This includes:

Unit Testing: Testing each individual feature in the application.

Integration Testing: Checks the integrity of the application to ensure everything works together.

System Testing: Includes the testing of the whole system.

User Acceptance Testing (UAT): In this testing, users check the application as per their needs.

2. Performance Testing

It’s done to check the overall performance of the application:

Load Testing: Testing the app under expected user load.

Stress Testing: Testing the app under extreme load or conditions.

Scalability Testing: Testing the application’s ability to scale.

3. Security Testing

Checking for vulnerabilities in the app:

Penetration Testing: Performing attacks on the app to find vulnerabilities.

Risk Assessment: Finding potential risks in the web app.

4. Usability Testing

Checking the user-friendliness of the app:

User Interface (UI) Testing: Ensuring the user interface is not too complex and looks attractive.

Accessibility Testing: Checking if the application is accessible to all.

5. Compatibility Testing

Ensuring the app is compatible with all required systems, devices, and browsers:

Browser Compatibility Testing: Testing the app across various browsers.

Device Compatibility Testing: Testing the app on various devices and systems.

6. Regression Testing

Checks whether the updated code does not affect the other functionality of the application:

Automated Regression Testing: Using automated tools to test.

Manual Regression Testing: Testing the app manually to ensure everything works as expected.

What is DevSecOps?

DevSecOps stands for Development, Security, and Operations. It integrates security into the DevOps practice, ensuring a safe development lifecycle.

It involves:

Integrating security at every stage of the software development process.

Encouraging collaboration between developers, security specialists, and operations teams.

Building software that is both efficient and secure.

Various SAST and DAST tools, differences between them

These are two best approaches to test an application:

1. SAST (Static Application Security Testing) Tools

Analyzes the source code of the program to find vulnerabilities without executing it.

Allows developers to find and fix vulnerabilities early in the development cycle.

Common vulnerabilities detected:

SQL Injection

Buffer Overflows

XML External Entity (XXE) Attacks

Popular SAST Tools:

Klocwork: A static code analyzer for C, C++, C#, Java, JavaScript, and Python.

Checkmarx: Supports multiple programming languages.

2. DAST (Dynamic Application Security Testing) Tools

Scans running software applications in real-time to find vulnerabilities.

Tests the application as it runs and has no access to its source code.

Key features:

Simulates an outsider attacker’s perspective.

Detects security vulnerabilities that SAST cannot.

Can test APIs, web services, and misconfigurations in servers or databases.

Popular DAST Tools:

Arachni: An open-source tool based on the Ruby framework, capable of detecting vulnerabilities like XSS, SQL injection, NoSQL injection, Code injection, and File inclusion variants.

Conclusion:

Both SAST and DAST are crucial for software security testing. Combining them offers a stronger approach to security at different stages of development.

How to Secure Web Applications Efficiently

1. Secure Coding Practices

Input Validation: Sanitize user inputs to prevent injection attacks.

Use Parameterized Queries: Prevent SQL injection by using parameterized queries instead of dynamic SQL.

Secure Authentication: Implement strong authentication mechanisms like MFA.

2. Regular Updates and Patching

Keep Software Up-to-Date: Regularly update and patch software, frameworks, and libraries.

Third-Party Dependencies: Regularly check and update third-party dependencies to ensure they are free of vulnerabilities.

3. Encrypt Data

Transport Layer Security (TLS): Use TLS to encrypt data transmissions between client and server.

Encrypt Sensitive Data: Encrypt sensitive data stored in databases and storage mediums.

4. Implement Security Headers

Use headers like Content Security Policy (CSP), Strict-Transport-Security (HSTS), and X-Content-Type-Options to mitigate security risks.

5. Regular Security Testing

Static and Dynamic Analysis: Use SAST and DAST to find vulnerabilities.

Penetration Testing: Simulate real-life attacks to find vulnerabilities.

6. Secure Configuration

Least Privilege: Follow the principle of least privilege for accessing databases, APIs, and other resources.

Environment Hardening: Disable unnecessary services, ports, and features to reduce attack surfaces.

7. Secure APIs

Authentication and Authorization: Implement strong mechanisms for APIs.

Rate Limiting: Use rate limiting to prevent denial-of-service attacks.

8. Monitor and Respond

Logging and Monitoring: Monitor logs to detect and respond to security threats.

Incident Response Plan: Develop a well-defined plan to minimize damage from attacks and security breaches.

Labs:

Lab 1:

OS Command Injection Lab

Status: Completed

Lab 2:

WebSockets Lab

Status: Completed

