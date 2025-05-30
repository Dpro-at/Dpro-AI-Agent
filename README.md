# 🧠 Dpro AI Agent

**Dpro AI Agent** is a cross-platform, open-source desktop assistant that lets anyone run powerful AI models (LLMs, Whisper, etc.) locally or remotely — no technical skills required.

Designed for:
- 💬 Everyday users seeking a smart, local AI assistant
- 🔐 Privacy-focused environments (100% offline by default)
- 👨‍💻 Developers who want to extend or embed AI workflows

---

## 🚀 Features

- 🧠 Plug-and-play support for open-source AI models (LLaMA, GPT4All, Whisper, etc.)
- 🔌 Local-first design with optional remote cloud deployment
- 📦 Works offline — no account, no telemetry, no cloud dependency
- 💻 Modern animated UI built with Tauri + React + Tailwind + Framer Motion
- 🧹 Modular and extensible architecture for developers

---

## 📦 Installation

### Requirements

- [Node.js](https://nodejs.org/) (LTS)
- [Rust](https://www.rust-lang.org/)
- [Python 3.10+](https://www.python.org/)
- (Optional) Git, Tauri CLI

### Quick Start

```bash
git clone https://github.com/YOUR_ORG/dpro-ai-agent.git
cd dpro-ai-agent
./install.sh
npm run tauri dev
```

> Note: The backend currently runs in Python. In future releases, Python will be bundled into a single executable.

---

## 📁 Folder Structure

```
dpro-ai-agent/
├── .github/                     # CI, PR templates
├── frontend/                    # React + Tailwind UI
├── ai_backend/                  # Python FastAPI for local AI models
├── src-tauri/                   # Tauri (Rust) backend and config
├── user_data/                   # Encrypted local storage
├── install.sh                   # Installer script
├── README.md                    # This file
├── CONTRIBUTING.md              # Contribution guidelines
└── LICENSE                      # Open source license
```

---

## 🔐 Privacy

Your data remains fully under your control — **the assistant runs entirely on your local machine by default**, with no connection to any external servers and no data transmission or tracking of any kind.

We do **not collect, process, analyze, or store any user data**. All models, prompts, configurations, and chat histories are stored locally and **encrypted at rest**, ensuring your personal information is safe and private.

For advanced use cases, the assistant can be **self-hosted on your own cloud server (e.g., VPS)**. You can configure a **custom DNS** to access your agent remotely and securely, giving you full flexibility to use it both inside and outside your local network — without ever relying on third-party services.

No telemetry, no analytics, no hidden sync — **Dpro AI Agent is designed from the ground up for privacy-first, user-owned AI**.

---

## 🤝 Contributing

We welcome developers to help improve the project!

### 🔧 Contribution Guidelines

- Only **complete and working features** are accepted
- Update documentation if your feature changes behavior
- Pass all formatting and test checks

📄 See [`CONTRIBUTING.md`](CONTRIBUTING.md) for full details.

### 🥪 Developer Test Command

```bash
npm run tauri dev
```

---

## 📜 License

This project is **free for individual use**.  
Commercial use requires a license — see [`LICENSE`](LICENSE).

---

## 📬 Contact

Questions, ideas, or business inquiries?  
📧 Email: **opensource@dpro.dev**

> Built with ❤️ by [Dpro](https://dpro.dev) — your trusted AI infrastructure partner.
