> ## ⚠️ PATCHED — but you can unpatch it.
>
> This project is currently **patched** and no longer works as intended.
> If you know what you're doing, it's possible to **unpatch/fix it yourself** — I'm just too lazy to maintain it.
>
> **PRs are welcome. 😴**

A high-performance, multi-threaded viewbot/solver for guns.lol profiles. It automatically bypasses Cloudflare Turnstile and solves the Proof-of-Work (PoW) challenges using an embedded WASM engine.

## Features

- 🚀 **Multi-threaded:** Run as many concurrent threads as your proxies can handle.
- 🧩 **Auto-Solver:** Solves Turnstile and PoW automatically.
- 🔄 **Proxy Support:** Automatically rotates through your proxies.
- 📊 **Live Stats:** Clean CLI interface with real-time stats in the window title.

---

## 🛠️ Installation

You have two options to run the bot:

### Option 1: Download Compiled Version (Easiest)

1. Go to the **Releases** page.
2. Download the latest `guns-viewbot.zip`.
3. Extract the ZIP file to a folder.
4. Fill in `config.json` and `proxies.txt` (see Configuration below).
5. Run the `.exe` file!

### Option 2: Compile Yourself (For Developers)

If you want to build the bot from the source code, you need to have [Golang](https://go.dev/dl/) installed.

1. Clone this repository or download the source code.
2. Open a terminal/CMD in the folder.
3. Build the executable:

```shell
go build -o guns-viewbot.exe .