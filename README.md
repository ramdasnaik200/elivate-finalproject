
# 🔍 Web Application Vulnerability Scanner with GUI

A Python-based automated vulnerability scanner for web applications, featuring a modern Flask GUI. It scans for **OWASP Top 10** vulnerabilities such as SQL Injection, XSS, Command Injection, Open Redirects, and more.


---

## 📌 Features

- ✅ Detects common OWASP Top 10 vulnerabilities
- 💉 Payload-based injection with response analysis
- 📊 Real-time scanning with results shown on a simple Flask GUI
- 🧠 Smart pattern matching and reflection-based detection
- 💡 Simple and modular codebase for easy customization

---


---



## ⚔️ Vulnerabilities Covered

This tool includes checks for the following OWASP Top 10 categories:

| Vulnerability            | Technique                          |
|--------------------------|------------------------------------|
| SQL Injection            | Error-based and reflective payloads |
| Cross-Site Scripting (XSS) | Script injection in input fields |
| Command Injection        | Shell payloads in parameters       |
| Open Redirect            | URL redirection parameter abuse    |
| Host Header Injection    | Host override in headers           |
| Unvalidated Input        | Reflective input in response       |

---


## 🧪 Example Usage

```bash
Target URL: http://testphp.vulnweb.com
```

- Automatically injects multiple payloads
- Matches reflected content or error patterns
- Displays findings directly in the web interface

---

## 📚 References

- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- [Flask Documentation](https://flask.palletsprojects.com/)
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/)

---

## 🛡️ Disclaimer

> This project is intended **for educational and authorized testing purposes only**.  
> Do not scan or attack targets without proper authorization.

---

## 🤝 Contributing

Feel free to fork this repo and improve it! Add detection methods, better payloads, or even enhance the UI.  
Pull requests are welcome. 🚀

---

## 📬 Contact

**Author:** Ramdas Naik  


---
