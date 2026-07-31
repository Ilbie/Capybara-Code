<p align="center">
  <img src="logo.png" alt="Capybara Code Logo" width="200"/>
</p>

<h1 align="center">Capybara Code (`capy`)</h1>

<p align="center">
  <b>An experimental, high-performance AI coding agent & harness for GPT models.</b>
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-Apache%202.0-blue.svg" alt="License"></a>
  <a href="#"><img src="https://img.shields.io/badge/Status-Coming%20Soon-red.svg" alt="Status"></a>
  <a href="#"><img src="https://img.shields.io/badge/Source-Pre--release-orange.svg" alt="Source"></a>
  <a href="#"><img src="https://img.shields.io/badge/Runtime-Bun%20%2B%20Rust-black.svg" alt="Runtime"></a>
</p>

---

> [!IMPORTANT]
> **Coming Soon:** Capybara Code is currently under initial preparation and internal development. **The source code, installation packages, and pre-built binaries have not been uploaded or published yet.** Stay tuned for the upcoming initial open-source release!

---

## 💡 Overview

**Capybara Code** is an experimental open-source AI coding agent designed to explore the frontiers of AI-assisted software engineering. Inspired by tools such as Codex and OpenCode, it aims to build a fast, transparent, and extensible coding harness around GPT models.

While model capability is essential, Capybara Code investigates how much performance, reliability, and precision can be gained through an improved agent harness—combining a rich Terminal UI, an isolated Rust execution sidecar, transactional file mutations, and multi-agent workflows.

---

## ✨ Planned Features

- 💻 **Interactive Terminal UI (TUI):** Real-time task logs, live token/context tracking, cost estimation, and status indicators.
- ⚡ **Rust-Powered Sidecar:** Safe, transactional file editing with optimistic concurrency, diff reviews, and rollback checkpoints.
- 🔑 **Dual Provider Support:** Direct OpenAI API integration (`capy auth api`) or official ChatGPT/Codex plan support (`capy auth login`).
- 🤖 **Sub-Agent Workflows:** Task delegation across specialized roles (`explore`, `executor`, `architect`, `reviewer`, `test`).
- 🔌 **Extensible Ecosystem:** Support for Model Context Protocol (MCP) servers and reusable `SKILL.md` workflows.
- 🔍 **Context Engine & Repository Map:** Smart symbol search, instruction parsing (`AGENTS.md`), and automated context selection.
- 🤖 **Headless & Automation Mode:** Run tasks non-interactively (`capy run --jsonl`) with machine-readable JSONL event streams.

---

## 🚀 Getting Started (Upcoming)

> [!NOTE]
> Source code and build scripts will be made publicly available upon the initial source release.

### Prerequisites (Planned)

- **[Bun](https://bun.sh/)** (>= 1.3.0)
- **[Rust](https://www.rust-lang.org/)** (>= 1.85 / Stable)

### Expected Setup Workflow

```bash
# (Coming Soon) Clone and build locally once source is published
git clone https://github.com/capybara-code/capybara-code.git
cd capybara-code

bun install
cargo build -p cbc-runtime
bun run capy
```

---

## 🎯 Project Goals

Capybara Code is built to explore how much performance can be gained through a better AI coding harness—not only through stronger models.

The long-term goal is to build a state-of-the-art coding agent with strong planning, tool use, context management, verification, and multi-agent workflows.

---

## 🤝 Contributing & Community

Issues, ideas, and feedback are welcome! 

Star or watch this repository to receive updates when the initial source code and developer preview are officially released.

---

## 📄 License

Licensed under the **[Apache License 2.0](LICENSE)**.
