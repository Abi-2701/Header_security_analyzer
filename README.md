# Header Security Analyzer

## Overview

Header Security Analyzer is a Python-based cybersecurity project designed to analyze both website security headers and email authentication headers. The project helps identify missing security configurations in websites and validates email authentication mechanisms such as SPF, DKIM, and DMARC.

This project demonstrates fundamental concepts of web security, email security, reconnaissance, and security assessment.

---

## Features

### Website Header Scanner

* Retrieves HTTP response headers from a website
* Checks for important security headers
* Detects missing security configurations
* Performs basic security assessment

Security Headers Checked:

* X-Frame-Options
* Content-Security-Policy (CSP)
* Strict-Transport-Security (HSTS)
* X-Content-Type-Options

### Email Header Analyzer

* Analyzes email authentication records
* Validates SPF status
* Validates DKIM status
* Validates DMARC status
* Generates a basic risk assessment

---

## Technologies Used

* Python 3
* Requests Library
* File Handling
* HTTP Protocol Concepts
* Email Security Concepts

---

## Project Structure

```text
header-security-analyzer/
│
├── website_header_scanner.py
├── email_header_analyzer.py
├── sample_email_header.txt
├── requirements.txt
├── README.md
└── screenshots/
    ├── website_output.png
    └── email_output.png
```

---

## Installation

```bash
git clone https://github.com/Abi-2701/header-security-analyzer.git

cd header-security-analyzer

pip install -r requirements.txt
```

---

## Usage

### Website Header Scanner

```bash
python website_header_scanner.py
```

Example Input:

```text
https://google.com
```

The scanner retrieves website headers and checks for important security configurations.

### Email Header Analyzer

```bash
python email_header_analyzer.py
```

The analyzer reads a sample email header file and validates SPF, DKIM, and DMARC authentication records.

---

## Sample Output

### Website Header Scanner

* Retrieves HTTP response headers
* Identifies missing security headers
* Displays security assessment results

### Email Header Analyzer

* SPF Validation Status
* DKIM Validation Status
* DMARC Validation Status
* Risk Assessment Level

---

## Cybersecurity Concepts Demonstrated

### Web Security

* HTTP Headers
* Security Misconfiguration Detection
* Information Gathering
* Website Reconnaissance

### Email Security

* SPF (Sender Policy Framework)
* DKIM (DomainKeys Identified Mail)
* DMARC (Domain-based Message Authentication)
* Phishing Prevention Basics

---

## Learning Outcomes

* Understanding HTTP Security Headers
* Understanding Email Authentication Mechanisms
* Python Scripting for Cybersecurity
* Basic Security Assessment Techniques
* Security Configuration Analysis

---

## Future Improvements

* Real-Time Email Header Parsing
* Advanced Header Risk Scoring
* Domain Reputation Analysis
* Security Report Generation (PDF/CSV)
* GUI Version
* Multi-Website Scanning Support

---

## Author

**Abishaa**

GitHub: https://github.com/Abi-2701

---

## License

This project is licensed under the MIT License.
