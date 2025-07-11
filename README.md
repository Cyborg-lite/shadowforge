
# Shadowforge OS

**Shadowforge** is a minimal operating system I'm building from scratch in Rust.

The goal is to create a lightweight OS designed only to:
- 🧠 Run local AI models, agents, and tools
- 🔐 Prioritize user privacy, control, and simplicity
- ⚙️ Avoid bloat, tracking, and unnecessary services

---

## ✍️ What This Project Is

This project is my journey to apply that knowledge and build something real over the next 6–7 months.

**Shadowforge is not meant to be a Linux replacement.**  
It’s a focused OS: clean, silent, and built only for running personal AI tools and respecting privacy.

---

## 📆 6–7 Month Realistic Plan (as a Rust beginner)

| Month | Focus                          | Goals                                                                 |
|--------|--------------------------------|-----------------------------------------------------------------------|
| 1      | 🦀 Learn Rust & OS Basics      | Complete Rustlings + Rust Book, understand `no_std`, `x86_64`, boot process |
| 2      | 🔧 Bootable Kernel             | Write bootloader, print to screen, load Rust kernel in QEMU |
| 3      | 🧱 Keyboard + Memory           | Input from keyboard, display output, build memory system |
| 4      | 🐚 Shell + Filesystem          | Build minimal shell and load fake apps from disk |
| 5      | 🧠 AI Layer (WASM/Python)      | Run basic AI logic using small models or agents |
| 6      | 🧪 Test + Clean + Write Docs   | Clean code, write documentation, release alpha version |
| 7      | ⏳ Buffer/Refine (Optional)    | Add polish, bug fixes, explore feedback or testing |

---

## 🛠️ Tech Stack

- Language: **Rust**
- Target: `x86_64`, bare metal (no Linux)
- Tools: `cargo`, `bootimage`, `QEMU`, `no_std`
- AI: Simple model runners (WASM or Python bridge)
- Interface: CLI only (no GUI planned initially)



