# 🔍 Cyber Scanner (XSS CLI Tool)

A simple command-line based **Cross-Site Scripting (XSS) vulnerability scanner** built in C++ using libcurl.
This tool tests web inputs using common XSS payloads and reports potential vulnerabilities.

---

## 🚀 Features

* 🔎 Scans a target URL with multiple XSS payloads
* 📂 Loads payloads from an external file
* ⚡ Fast CLI-based execution
* 📝 Saves scan results to a report file
* 🧪 Beginner-friendly cybersecurity project

---

## 🛠️ Tech Stack

* **Language:** C++
* **Library:** libcurl
* **Environment:** Linux / WSL
* **Concepts Used:**

  * File Handling
  * HTTP Requests
  * CLI Development
  * Basic Security Testing

---

## 📂 Project Structure

cyber-scanner/
├── scanner.cpp        # Main scanner logic
├── payloads/
│   └── xss.txt        # XSS payload list
├── report.txt         # Output results
├── README.md

---

## ▶️ How to Run

### 1. Compile

```bash
g++ scanner.cpp -lcurl -o scanner
```

### 2. Run

```bash
./scanner
```

---

## 🧪 Example Payloads

```html
<script>alert(1)</script>
'><script>alert(1)</script>
" onmouseover=alert(1)
```

---

## ⚠️ Disclaimer

This tool is created for **educational purposes only**.
Do NOT use it on websites without proper authorization.

---

## 📌 Future Improvements

* 🔍 Detect real vulnerability (response analysis)
* 🌐 Support multiple URLs
* 🧵 Add multithreading (performance boost)
* 📊 Better reporting system

---

## 👨‍💻 Author

**Shashank Swaraj**

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and feel free to contribute!
