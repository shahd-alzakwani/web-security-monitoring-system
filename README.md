# Web Security Monitoring System

## Overview
This project is a simple web security system developed as a graduation project. It focuses on detecting suspicious activities and protecting web applications from common attacks.

## Features
- Detects multiple failed login attempts
- Sends email alerts after 3 unsuccessful login attempts
- Basic protection against Cross-Site Scripting (XSS) attacks
- Encodes user input to prevent malicious script execution

## How It Works
The system monitors login attempts made by users. If a user fails to log in three times consecutively, an automatic email alert is triggered and sent to the administrator.

For security, the system also handles user input carefully by encoding it before displaying it on the web page. This prevents attackers from injecting harmful scripts (XSS attacks).

## Technologies Used
- Python (Flask)
- HTML / CSS
- SQLite (or your database if different)
- Email handling (SMTP)

## Purpose
The purpose of this project is to demonstrate basic web security concepts and show how simple techniques can protect systems from common vulnerabilities.

## Screenshots

### Email Alert System
![Screenshot 2025-04-18 181528.png)

### System Architecture
![Architecture](PUT-LINK-HERE)

### Code Execution (Python - Flask)
![Code](PUT-LINK-HERE)

### Encrypted Page Example
![Encrypted Page](PUT-LINK-HERE)

## Author
Shahd Abdullah Al-Zakwani
