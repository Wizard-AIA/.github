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

Your data never leaves your machine unless you choose a remote cloud provider. Powered by a modular **Tri-Model Architecture** (Manager, Worker, and Embeddings). No API key is required — local [Ollama](https://ollama.com/) or [LM Studio](https://lmstudio.ai/) models running locally are all it takes.

**[📖 Documentation](https://wizardw2.vercel.app/docs)** · **[🚀 Quickstart](https://wizardw2.vercel.app/docs/getting-started/installation)** · **[🌐 Live Website](https://wizardw2.vercel.app/)** · **[💬 Discussions](https://github.com/Wizard-AIA/Wizard-w2/discussions)** · **[📦 Latest Release](https://github.com/Wizard-AIA/Wizard-w2/releases/latest)**

---

## ⚡ Install & Quick Start

### 🍺 Option A: Homebrew (macOS & Linux)
```bash
brew install Wizard-AIA/wizard/wizard
```

### 🚀 Option B: 1-Command Installers

**Linux & macOS:**
```bash
curl -fsSL https://wizardw2.vercel.app/install.sh | sh
```

**Windows (PowerShell 5.1 or 7):**
```powershell
irm https://wizardw2.vercel.app/install.ps1 | iex
```

Then, from any directory:

```bash
wizard --version  # confirm the install
wizard init       # choose a provider and models, install what is missing
wizard start      # launches Wizard and opens http://localhost:3000
wizard doctor     # if anything looks wrong: checks the install and says how to fix it
```

### ☁️ Option C: 1-Click Cloud Trial (GitHub Codespaces)
[![Open in GitHub Codespaces](https://img.shields.io/badge/Codespaces-Open_in_Browser-blue?logo=githubcodespaces&logoColor=white)](https://codespaces.new/Wizard-AIA/Wizard-w2)

### 🐳 Option D: Docker Compose
```bash
git clone https://github.com/Wizard-AIA/Wizard-w2.git
cd Wizard-w2
docker compose up -d
```

### 📦 Option E: Standalone Prebuilt Packages

Prebuilt archives for macOS (Apple Silicon and Intel), Linux (x86-64 and ARM64) and Windows (x86-64), with a `SHA256SUMS` file, are on the **[latest release page](https://github.com/Wizard-AIA/Wizard-w2/releases/latest)**. Check the archive against `SHA256SUMS`, extract it, then from the extracted `Wizard-v<version>-<platform>` folder run `./cli/wizard init` and `./cli/wizard start`.

Open **http://localhost:3000** to begin analyzing your data. Nothing above needs administrator rights.

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
