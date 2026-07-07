# 🔐 RSA Encrypted Group Chat App

<p align="center">
  <img src=""F:\linkedin\RSA_chatbot_banner.jpeg"" width="100%">
</p>
Welcome to my **secure group chat application** built with Python! This app lets multiple users chat with each other in real-time, using **end-to-end RSA encryption** to keep every message private.

It supports both **GUI** (with a clean interface) and **CLI** (command-line) modes for both the **server** and **clients**—so whether you're a terminal lover or prefer buttons and windows, you're covered.

---

## 🌟 What It Can Do

- 🧠 **RSA Encryption:** Messages are encrypted before being sent and decrypted on the receiver’s end.
- 👥 **Multiple Clients:** Several users can join the same server and chat together.
- 🖥️ **Easy GUI Mode:** Launch chat windows with a user-friendly interface.
- 💻 **Powerful CLI Mode:** Use the app entirely through the terminal if you prefer.
- 📣 **Server Broadcasts:** The server can also send messages to everyone.
- 🧵 **Threaded Connections:** Every client runs on its own thread, so chatting is smooth.

---

## 🧰 Files in This Project

- `rsa.py` – Generates RSA keys and handles message encryption/decryption.
- `client_gui.py` – A graphical chat client.
- `client_cli.py` – A terminal-based chat client.
- `server_gui.py` – A graphical server interface that shows connected clients.
- `server_cli.py` – A terminal-based server.
- `launcher.py` – Handy starter menu to launch any of the above with one click.

---

## 🚀 How to Run It

### ✅ Step 1: Requirements

This app only needs **Python 3.8+**. No external libraries needed. It uses built-in modules like `socket`, `tkinter`, and `pickle`.

---

### ✅ Step 2: Start the App

You can run the launcher to get started quickly:

```bash
python launcher.py
```

Then just click on **Start Server** or **Start Client**, depending on what you want to do.

---

### ✅ Or Run Individual Files

If you prefer manual control, you can run these directly:

- Start the server:
  ```bash
  python server_gui.py
  # or
  python server_cli.py
  ```

- Start a client:
  ```bash
  python client_gui.py
  # or
  python client_cli.py <server_ip> <port>
  ```

---
## 🙋 About the Author

This project was built as a fun and educational way to explore encryption, networking, and GUI development—all in one place.  
Feel free to explore, improve it, or just use it as-is for secure chatting in your LAN!
