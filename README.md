# JXSS: XSS Vulnerability Detection & Exploitation Tool  

JXSS is a Python-based tool designed to detect and exploit Cross-Site Scripting (XSS) vulnerabilities in web applications. Built with modularity and flexibility in mind, JXSS can help penetration testers, bug bounty hunters, and cybersecurity enthusiasts identify potential security weaknesses in JavaScript files and inline scripts.  

---

## 🚀 Features  

- **JavaScript Vulnerability Detection**: Scans external JavaScript files and inline scripts to detect XSS vulnerabilities.  
- **Payload Injection**: Supports custom payloads for testing successful exploitation.  
- **Automated Dynamic Testing**: Uses Selenium to automate testing of parameters and detect XSS vulnerabilities in real-time.  
- **Detailed Reporting**: Outputs a clear summary of vulnerabilities and successful payloads for easy documentation.  

---

## 
---

## 🛠️ Installation  

1. **Clone the Repository**:  
```bash
git clone https://github.com/John-A0/JXSS.git
cd JXSS
   ```
2. **Install Requirements**:
JXSS uses Python 3.x. Install dependencies using:
  ```bash
  pip install -r requirements.txt
  ```
3. **Set Up WebDriver**:
Install the Chrome WebDriver using webdriver_manager:
  ```bash
  pip install webdriver-manager
  ```

## ⚡ Usage
1. **Basic Scanning**
Run the tool and provide the URL to scan for JavaScript-based XSS vulnerabilities:
  ```bash
  python JXSS.py
  ```
You’ll be prompted to:

- Enter the URL to scan.
- Provide the path to your payload wordlist.
  
2. **Aggressive Exploitation (Parameter Testing)**
After scanning, you can use Selenium for aggressive XSS testing:

Enter a URL with parameters to test payloads dynamically.
JXSS will automate testing and handle alerts for detected vulnerabilities.

## 📂 Payload Wordlist
JXSS requires a payload wordlist to test for XSS vulnerabilities. You can use existing wordlists like those from @SecLists or create your own.

## 🧩 Roadmap
Add support for bypassing Web Application Firewalls (WAFs).
Enhance performance with asynchronous requests.
Introduce JSON/HTML output for better reporting.
Add more advanced detection techniques for modern web apps.

## 🛡️ Disclaimer
This tool is intended for educational purposes and authorized testing only. Unauthorized use on systems without explicit permission is illegal and unethical.

## 🤝 Contributing
Contributions are welcome! Feel free to fork the repo, submit pull requests, or open issues for suggestions and bug reports.

## 💌 Contact
Have feedback or want to collaborate? Connect with me on LinkedIn --> https://www.linkedin.com/in/john-aymn/

