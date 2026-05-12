### Dependencies
Install the required dependency:

```bash
pip install termcolor
```

---

## ▶️ Usage

![Alt text](phase_1-1.png)

1. First, start the server:
```bash
python server.py
```

2. Then, in a separate terminal, start the client:
```bash
python client.py
```

3. Type and send messages. To exit:
```
/exit
```

### ⚠️ Notes:
- Use separate terminal windows for server and client.
- CMD or PowerShell may not support `termcolor` — comment out colored lines if needed.
- Ensure previous instances are terminated before restarting to avoid port conflicts.
- For CMD users: comment `termcolor` lines and uncomment simple print statements.

---