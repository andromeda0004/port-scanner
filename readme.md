# 🔍 Python Port Scanner

A simple Python-based TCP port scanner that checks for open ports on a given IP address or hostname.

---

## 🚀 Features

- Resolves a hostname to its IP address.
- Scans ports from `1` to `65535` using TCP `connect()` method.
- Reports open ports in real time.
- Displays timestamp and scan target.
- Command-line based; works on Linux/macOS (can be adapted for Windows).

---

## 💪 Requirements

- Python 3.x

No external libraries required (uses only Python’s standard library: `socket`, `subprocess`, `datetime`).

---

## 📦 Usage

### 1. Save the Script

Save the script as `scanner.py`.

---

### 2. Run the Script

```bash
python3 scanner.py
```

Enter the target IP or hostname when prompted.

---

## ⚠️ Notes

- The script uses `subprocess.call('clear')` which works on Unix/Linux/macOS.  
  On Windows, change that line to:
  ```python
  subprocess.call('cls', shell=True)
  ```

- Scanning all 65535 ports may take time. You can modify the port range as needed.

---

## 🛡️ Legal Disclaimer

This tool is for **educational purposes only**. Do **not** scan systems you don’t own or have permission to test. Unauthorized scanning may be illegal.

---

