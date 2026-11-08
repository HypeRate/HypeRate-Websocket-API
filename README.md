# HypeRate WebSocket API

Public-safe demos and documentation for the **HypeRate WebSocket API (heart rate only)**.

- 🌐 Browser demo (GitHub Pages–ready)
- 🧩 Node.js / TypeScript demo
- 📘 API documentation (Markdown)
- 🔒 No API keys included

> This repository is a **developer reference & demo**, not a full SDK.

---

## Get an API Key

You can request an API key here:  
👉 **https://hyperate.io/api**

---

## Repository Structure

```
.
├─ web/        # Browser demo (public-safe, GitHub Pages)
├─ node-ts/    # Node.js / TypeScript demo
├─ docs/       # API documentation (Markdown)
├─ SECURITY.md
└─ .gitignore
```

---

## Security Notice (Public Repository)

- API keys are **never included**
- Do not commit keys or paste them into issues or screenshots
- Browser demo stores credentials only locally (optional, via localStorage)

---

## GitHub Pages

Publish `main` → `/docs` in **Settings → Pages**. The demo is then available at:
https://hyperate.github.io/HypeRate-Websocket-API/

The matching local demo is in `web/index.html`. Keep both HTML files in sync.

Users paste their API key locally — no credentials are shipped with this repo.

---

## Documentation

- [WebSocket API – Heart Rate Only](docs/WEBSOCKET_API.md)

## Official repository

Target repository: [HypeRate/HypeRate-Websocket-API](https://github.com/HypeRate/HypeRate-Websocket-API). This project replaces the former `HypeRate/DevDocs` documentation.
