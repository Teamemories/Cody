# 🤖 Cody

> Cody is a lightweight model wrapper implemented as an experimental configuration derived from a subset of the [`Qwen3.5`](https://ollama.com/library/qwen3.5) architecture.
> This system is designated strictly for educational and research applications at the student level.
> It should be classified as a scientific experiment rather than a commercial product or an official release.

## How to install

1. Install Ollama App on your PC

- **Windows:**

> download setup file from [`ollama.com`](https://ollama.com/download/windows)

> or run this script on PowerShell:

```ps1
irm "https://ollama.com/install.ps1" | iex
# or
winget.exe install --id Ollama.Ollama
```

- **MacOS:**

> download setup file from [`ollama.com`](https://ollama.com/download/mac)

> or run this script on Terminal:

```bash
curl -fsSL https://ollama.com/install.sh | sh
```

- **GNU/Linux:**

> run this script on Terminal:

```bash
curl -fsSL https://ollama.com/install.sh | sh
```

2. Pull Model

- open terminal: ```ollama pull cmd_er/cody``` (wait to download complete)

3. Run model

- open terminal ```ollama serve``` and in another terminal page ```ollama run cmd_er/cody```
- or open Ollama app and select `cmd_er/cody` from model list.

### ❗Note

> **Cody is not affiliated with, endorsed by, or distributed as an official artifact of the original model provider.**
