
# Simple Keylogger 🖥️🔑

This is a basic Python keylogger that records user keystrokes and stores them in a log file. It uses the `pynput` library to monitor keyboard events in real time.

> ⚠️ **Disclaimer:** This project is for educational purposes only. Do not use it to log keystrokes on devices you do not own or without the user's explicit permission. Unauthorized use is unethical and illegal.

---

## 🚀 Features

- Logs keystrokes to a file (`log.txt`)
- Automatically writes to file after every 10 keystrokes
- Exits gracefully when the `Escape (Esc)` key is pressed

---

## 🛠️ Requirements

- Python 3.x
- [`pynput`](https://pypi.org/project/pynput/)

Install it with:

```bash
pip install pynput
```

---

## 📄 How It Works

1. The program listens for keyboard input.
2. It appends each key press to a list.
3. After every 10 keys, the data is written to `log.txt`.
4. Pressing the **Esc** key stops the listener.

---

## 💻 Usage

```bash
python keylogger.py
```

- Output will be saved to a file called `log.txt` in the same directory.

---

## 📌 Important Notes

- The script only logs printable characters.
- Spaces are logged as new lines for readability.
- Special keys like `Shift`, `Ctrl`, etc. are ignored in the final log.

---

## 🔒 Legal & Ethical Notice

This script is intended solely for **learning and testing** on **your own machine**. Using this for unauthorized surveillance or data collection is **illegal** and goes against ethical standards.

---

## 📁 Sample Output (log.txt)

```
hello
world123
```

---

## 📚 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

- [pynput Documentation](https://pynput.readthedocs.io/en/latest/)
