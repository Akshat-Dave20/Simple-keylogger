# 🛡️ Simple Keylogger (Python)

A basic Python-based keylogger using `pynput`. This tool captures keystrokes and logs them with timestamps to a local file.

> ⚠️ **DISCLAIMER**  
> This project is intended **strictly for educational purposes**, such as ethical hacking training, cybersecurity research, and penetration testing labs. **Do not use this tool on devices you do not own or have explicit permission to monitor.** Misuse can be illegal.

---

## 🚀 Features

- Logs all keyboard input
- Timestamps each keystroke
- Saves to a file (`keylog.txt`)
- Lightweight and easy to run

---

## 📦 Requirements

- Python 3.7 or newer
- [`pynput`](https://pypi.org/project/pynput/)

Install it with:

```bash
pip install pynput
```

---

## ▶️ Usage

Run the keylogger:

```bash
python keylogger.py
```

You should see:

```
[*] Keylogger started. Logging to keylog.txt
```

Stop with `CTRL + C`.

---

## 📁 Output

Keystrokes will be logged to a file called:

```
keylog.txt
```

Each entry includes a timestamp and the key pressed.

---

## 🧼 Clean Up

To remove logs:

```bash
rm keylog.txt
```

---

## 📝 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.
## ✒️ Author

cryptowolfx– built for ethical research, red teaming, and learning.  
Compatible with Kali Linux, Parrot OS, Ubuntu, and other Debian-based distributions.
