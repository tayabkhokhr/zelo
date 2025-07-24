# 💬 Zelo — Modern Desktop Chat App

&#x20;

Zelo is a fast, secure, and modern desktop chat application designed for seamless communication. Built with Python and PyQt6, Zelo brings a sleek UI, real-time messaging, Google authentication, and efficient contact management — all in one powerful package.

---

## 🚀 Features

- 🌐 **Google Sign-In** — Simple, secure authentication.
- 🗂️ **Smart Contact Management** — Automatically adds and organizes your chat contacts.
- 💬 **Real-Time Messaging** — Instantly send and receive messages with live sync.
- 🧑‍💻 **Modern UI** — Beautifully crafted with PyQt6 and custom styling.
- 🔐 **Encrypted Communication** *(optional)* — End-to-end encryption built in.
- 📁 **Lightweight Installer** — Includes desktop & Start Menu shortcuts.

---

## 🖥️ Screenshots

| Login Screen | Chat Window |
| ------------ | ----------- |
|              |             |

---

## 📆 Installation

### 🔹 Option 1: Using `zelosetup.exe` (Recommended for Windows)

1. [Download Zelo Setup](https://github.com/tayabkhokhr/zelo/releases)
2. Run the installer.
3. Launch Zelo from your desktop or Start Menu.
4. Log in with Google and start chatting!

### 🔹 Option 2: Run from Source (For Developers)

```bash
git clone https://github.com/yourusername/zelo.git
cd zelo
pip install -r requirements.txt
python main.py
```

> Make sure you have Python 3.10+ and PyQt6 installed.

---

## 🧰 Tech Stack

- **Frontend**: PyQt6
- **Backend**: Firebase (Auth & Firestore)
- **Language**: Python 3
- **Build Tool**: PyInstaller

---

## 📁 Project Structure

```
zelo/
├── app/
│   ├── main.py
│   ├── auth.py
│   ├── chat.py
│   └── ...
├── assets/
│   ├── zelo.ico
│   └── zelo.png
├── firebase_key_encrypted.bin
└── zelosetup.exe
```

---

## 🙌 Credits

Created with ❤️ by [Tayyab Khokhar](https://github.com/tayabkhokhr)\
Special thanks to the open-source Python and Firebase communities.

---

## 📜 License

This project is licensed under the MIT License. See [`LICENSE`](LICENSE) for more information.
