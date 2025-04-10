# 💻 Web-Based Reverse Shell Payload Generator and Host

A web application that allows penetration testers and ethical hackers to generate reverse shell payloads in various languages, host them via HTTP, save payloads to files, and launch listeners with ease — all from a single interface.

---

## 🚀 Features

- 🔧 Generate reverse shell payloads (Bash, Python, PHP, PowerShell, etc.)
- 📁 Save payloads directly to local files
- 🌐 Host payloads over HTTP using built-in server
- 🎧 Launch listeners (Netcat) automatically
- 🧠 User-friendly web interface with real-time feedback
- 🔐 Designed for internal testing and ethical hacking purposes only

---

## 🛠️ Tech Stack

- **Backend:** Python (Flask)
- **Frontend:** HTML, CSS, JavaScript (Bootstrap)
- **Platform:** Kali Linux
- **Other Tools:** Netcat, Python HTTP server

---

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/Pradeepkumaru-cyber/web-reverse-shell-generator.git

# Move into the project directory
cd web-reverse-shell-generator

# Install dependencies
pip install -r requirements.txt

# Run the Flask app
python app.py
