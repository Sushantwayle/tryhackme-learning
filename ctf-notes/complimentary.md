# TryHackMe: Complimentary

## Overview
A hands-on CTF challenge focused on investigating web application
behavior and understanding client-side code.

## Learning Objectives
- Inspect JavaScript code.
- Understand browser Local Storage.
- Investigate application authentication and identity configuration.
- Practice structured web application analysis.

## Investigation Process

### 1. JavaScript Analysis
Reviewed client-side JavaScript to understand how the application
handles user-related information.

### 2. Browser Storage
Investigated Local Storage to understand how browser-side data
was used by the application.

### 3. Identity and Data Services
Studied the application's identity configuration and explored
the relationship between authentication and data access.

## Key Takeaways
- Client-side JavaScript can reveal useful application logic.
- Browser storage should not be treated as a trusted security boundary.
- Authentication and authorization are different security concepts.
- Cloud identity and data-access configurations should be reviewed carefully.

## Tools and Techniques
- Browser Developer Tools
- JavaScript inspection
- Local Storage inspection
- HTTP request analysis

## Security Notes
This document focuses on learning and methodology.
Flags, credentials, tokens, and sensitive challenge data are not included.

## Further Learning
Continue practicing secure web application analysis and
cloud identity security.
## Technical Concepts Learned

### 1. Client-Side JavaScript
JavaScript runs in the browser and can reveal how a web application handles user interactions and application data.

### 2. Browser Local Storage
Local Storage allows a website to store data in the browser. Data stored there should not be trusted for authorization decisions.

### 3. Authentication vs Authorization
Authentication verifies identity, while authorization determines which resources or actions that identity is allowed to access.

### 4. Cloud Identity and Permissions
Cloud applications should use properly configured identity policies and access permissions to protect data and services.

## Reflection

This challenge helped me understand the importance of inspecting client-side application behavior and reviewing browser storage and cloud identity configurations.
