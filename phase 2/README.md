## ✅ Requirements

This project uses only built-in Python modules. No additional packages are needed.

---

## ▶️ How to Run

### 🟢 Start the Server

```bash
python server.py
```

### 🟠 Start One or More Clients (each in a new terminal)

```bash
python client.py
```

### 🔚 Exit the Chat
To disconnect from the chat, type:

```
/exit
```


## 🔍 Technical Highlights

- 🔁 TCP guarantees delivery and order of messages
- 🧵 Each client runs in its own thread on the server
- 🔤 Messages encoded/decoded in UTF-8
- 🧠 Easy to extend into full chatroom or GUI interface

## 📌 Future Improvements

- [ ] Implement message broadcasting
- [ ] Add user nicknames
- [ ] Support GUI client (e.g., with PyQt)
- [ ] Add TLS/SSL encryption
- [ ] Display list of active clients
