# 🧙‍♂️ Wizard

> **A local-first autonomous data analysis agent.** Ask real questions about your data; it investigates — looking, computing, revising its approach when the data disagrees with it — then verifies the result and explains it, streaming its reasoning as it goes.

[![Status](https://img.shields.io/badge/Status-Active-success)](https://github.com/Wizard-AIA/Wizard-w2)
[![Release](https://img.shields.io/github/v/release/Wizard-AIA/Wizard-w2?label=Release&color=orange&logo=github)](https://github.com/Wizard-AIA/Wizard-w2/releases/latest)
[![Homebrew](https://img.shields.io/badge/Homebrew-brew_wizard-2e7d32?logo=homebrew&logoColor=white)](https://github.com/Wizard-AIA/homebrew-wizard)
[![Codespaces](https://img.shields.io/badge/Codespaces-Open_in_Cloud-blue?logo=githubcodespaces&logoColor=white)](https://codespaces.new/Wizard-AIA/Wizard-w2)
[![Awesome](https://img.shields.io/badge/Awesome-Wizard-fc60a8?logo=awesomelists&logoColor=white)](https://github.com/Wizard-AIA/awesome-wizard)
[![OpenSSF Scorecard](https://img.shields.io/badge/OpenSSF_Scorecard-9.5%2F10-success?logo=openssf&logoColor=white)](https://scorecard.dev/viewer/?uri=github.com/Wizard-AIA/Wizard-w2)
[![Python](https://img.shields.io/badge/Python-3.12+-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](https://github.com/Wizard-AIA/Wizard-w2/blob/master/LICENSE)
[![Docs](https://img.shields.io/badge/Docs-wizardw2.vercel.app-6366f1?logo=vercel&logoColor=white)](https://wizardw2.vercel.app/)

<p align="center">
  <img src="https://raw.githubusercontent.com/Wizard-AIA/Wizard-w2/master/docs/assets/wizard-ui.png" alt="Wizard Interface Preview" width="100%" />
</p>

Your data never leaves your machine unless you choose a remote cloud provider. No API key is required — two small [Ollama](https://ollama.com/) or [LM Studio](https://lmstudio.ai/) models running locally are all it takes.

**[📖 Documentation](https://wizardw2.vercel.app/docs)** · **[🚀 Quickstart](https://wizardw2.vercel.app/docs/getting-started/installation)** · **[🌐 Live Website](https://wizardw2.vercel.app/)** · **[💬 Discussions](https://github.com/Wizard-AIA/Wizard-w2/discussions)** · **[📦 Latest Release (v1.0.5)](https://github.com/Wizard-AIA/Wizard-w2/releases/latest)**

---

## ⚡ Install & Quick Start

### 🍺 Option A: Homebrew (macOS & Linux)
```bash
brew tap Wizard-AIA/wizard && brew install wizard
wizard init && wizard start
```

### 🚀 Option B: 1-Command Automated Installers

**Linux & macOS:**
```bash
curl -fsSL https://wizardw2.vercel.app/install.sh | bash
```

**Windows (PowerShell):**
```powershell
irm https://wizardw2.vercel.app/install.ps1 | iex
```

### ☁️ Option C: 1-Click Cloud Trial (GitHub Codespaces)
[![Open in GitHub Codespaces](https://img.shields.io/badge/Codespaces-Open_in_Browser-blue?logo=githubcodespaces&logoColor=white)](https://codespaces.new/Wizard-AIA/Wizard-w2)

### 🐳 Option D: Docker Compose
```bash
git clone https://github.com/Wizard-AIA/Wizard-w2.git
cd Wizard-w2
docker compose up -d
```

### 📦 Option E: Standalone Prebuilt Packages (v1.0.5)

| Operating System | Architecture | Download Package |
| :--- | :--- | :--- |
| **macOS** | Apple Silicon (M1 / M2 / M3 / M4) | [**`Wizard-v1.0.5-darwin-arm64.zip`**](https://github.com/Wizard-AIA/Wizard-w2/releases/download/v1.0.5/Wizard-v1.0.5-darwin-arm64.zip) |
| **macOS** | Intel x86_64 | [**`Wizard-v1.0.5-darwin-amd64.zip`**](https://github.com/Wizard-AIA/Wizard-w2/releases/download/v1.0.5/Wizard-v1.0.5-darwin-amd64.zip) |
| **Linux** | x86_64 / amd64 | [**`Wizard-v1.0.5-linux-amd64.zip`**](https://github.com/Wizard-AIA/Wizard-w2/releases/download/v1.0.5/Wizard-v1.0.5-linux-amd64.zip) |
| **Linux** | ARM64 / aarch64 | [**`Wizard-v1.0.5-linux-arm64.zip`**](https://github.com/Wizard-AIA/Wizard-w2/releases/download/v1.0.5/Wizard-v1.0.5-linux-arm64.zip) |
| **Windows** | x86_64 | [**`Wizard-v1.0.5-windows-amd64.zip`**](https://github.com/Wizard-AIA/Wizard-w2/releases/download/v1.0.5/Wizard-v1.0.5-windows-amd64.zip) |

```bash
# After extracting your zip:
./cli/wizard init       # Checks prerequisites & installs environment
./cli/wizard start      # Starts backend + frontend daemon and opens your browser
```

Open **http://localhost:3000** to begin analyzing your data.

---

## 🏛️ Ecosystem Repositories

| Repository | Description |
|---|---|
| **[Wizard-w2](https://github.com/Wizard-AIA/Wizard-w2)** | **Core Engine:** FastAPI backend, analytical workspace, Apache Arrow streaming, OS sandboxing, and Go CLI supervisor. |
| **[website](https://github.com/Wizard-AIA/website)** | **Docs & Landing:** Official website, architectural documentation hub, and interactive web demo. |
| **[homebrew-wizard](https://github.com/Wizard-AIA/homebrew-wizard)** | **Package Manager:** Official Homebrew tap for one-command macOS and Linux installation (`brew install wizard`). |
| **[skills](https://github.com/Wizard-AIA/skills)** | **Skill Registry:** Community registry of curated `SKILL.md` domain modules the agent retrieves and executes mid-turn. |
| **[awesome-wizard](https://github.com/Wizard-AIA/awesome-wizard)** | **Ecosystem Hub:** Curated playbooks, sample datasets, local model recipes, and community integrations. |
| **[.github](https://github.com/Wizard-AIA/.github)** | **Community & Health:** Organization profile landing page, issue templates, and security policies. |

---

## 👥 Contributors

Thank you to everyone building and improving Wizard!

[![Contributors](https://contrib.rocks/image?repo=Wizard-AIA/Wizard-w2)](https://github.com/Wizard-AIA/Wizard-w2/graphs/contributors)

---

BSD-3-Clause Licensed. Created by **Aniket Saha** ([@Aniket-a14](https://github.com/Aniket-a14)). Contributions are welcome — see [CONTRIBUTING.md](https://github.com/Wizard-AIA/Wizard-w2/blob/master/CONTRIBUTING.md) to get involved.
