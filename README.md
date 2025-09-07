# project-web-scanner
# Web Application Vulnerability Scanner

A simple Python & Flask-based web vulnerability scanner to detect XSS, SQL Injection, and CSRF vulnerabilities in web applications.

## Features

- **Automated crawling** of target websites, discovering forms and inputs
- **Payload injection** for XSS and SQLi using multiple test payloads
- **CSRF token testing** in detected forms
- **Regex-based response analysis** to confirm vulnerabilities
- **Clean web interface** (Flask) for launching scans and viewing results
- **Severity rating** for discovered vulnerabilities
- **Stylish UI** for input and results pages

## Tools Used

- Python 3
- Flask
- Requests
- BeautifulSoup
- Regex (`re` module)
- OWASP Top 10 guidelines

## Usage

1. **Clone the repository**:
2.  https://github.com/<Abhinav0114>/<project-web-scanner>.git
cd <project-web-scanner>
2. **Install dependencies**:
3. pip install -r requirements.txt
4. **Run the application**:
5. python app.py
6. 4. **Open your browser** and go to `http://localhost:5000` to start scanning.

## Disclaimer
Only run this tool on websites you own or have explicit permission to test. Scanning third-party or production sites without permission is illegal and unethical.







