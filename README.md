<div align="center">

# ⌨️ Simple Keylogger

### *A Lightweight Python Tool for Educational Keystroke Logging*

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![PyPI](https://img.shields.io/badge/pynput-1.7.6-2b5b84?style=for-the-badge)](https://pypi.org/project/pynput/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Mr-B1nary)

<br>

---

## 📖 The Concept

> A minimalist keystroke logger built with Python to monitor and record keyboard inputs locally.  
> **Purpose:** Educational insight into event-driven programming and input handling.

<br>

---

## ⚠️ Legal & Ethical Notice

> **This tool is for educational and authorized testing only.**  
> Using this software on any system without explicit permission is **illegal** and **unethical**.  
> The developer assumes no responsibility for misuse. Always obtain proper authorization before use.

<br>

---

## ⚙️ How It Works

| Step | Action |
|:----:|:-------|
| 1️⃣ | Listens to global keyboard events using the `pynput` library |
| 2️⃣ | Captures both regular and special keys (space, enter, backspace) |
| 3️⃣ | Writes each key press with a timestamp to a local log file |
| 4️⃣ | Stops when the `ESC` key is pressed |

<br>

---



## 🚀 Quick Start

### Prerequisites

- Python 3.x
- `pynput` library

### Installation & Execution

```bash
git clone https://github.com/Mr-B1nary/SimpleKeylogger.git
```
```bash
cd SimpleKeylogger
```
```bash
pip install pynput
```
```bash
python main.py
```

> **Stop the script:** Press the `ESC` key at any time.

<br>

---

## 📝 Log Output Example

```
hel Key.space lo Key.enter
```

---

## 🧪 Compatibility

| OS | Status |
|:---|:------:|
| Windows 10/11 | ✅ Tested |
| Linux (Ubuntu) | ✅ Tested |
| macOS | ✅ Tested |

---

## 🔧 Customization Options

| Feature | How to Change |
|:--------|:--------------|
| Log file name | Modify `FILE = "keylog.txt"` |
| Stop key | Change `if key == Key.esc:` to your preferred key |
| Log format | Edit the `write_file()` function |

---







<br>



---

<div align="center">

### ⭐ If you found this useful, please consider giving it a star!

[![GitHub stars](https://img.shields.io/github/stars/Mr-B1nary/SimpleKeylogger?style=for-the-badge&logo=github&color=yellow)](https://github.com/Mr-B1nary/SimpleKeylogger/stargazers)





</div>
