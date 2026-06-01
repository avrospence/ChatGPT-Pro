# ChatGPT-Pro

A collection of 5 vibe-coding project ideas — useful, shippable fast, and ready to publish.

## Projects

### 1. AI Commit Message Generator
A CLI tool that reads your staged git diff and uses an LLM to write a commit message for you.

**Stack:** Python or Node.js + Claude/OpenAI API | **Build time:** ~1–2 hours | **Folder:** [`ai-commit/`](./ai-commit/)

### 2. Local File Chat
Drop a folder of PDFs or markdown docs and ask questions about them in your terminal. Fully local — no server, no auth.

**Stack:** Python + LlamaIndex + Ollama | **Build time:** ~2–3 hours | **Folder:** [`local-file-chat/`](./local-file-chat/)

### 3. PR Review Bot (GitHub Action)
A GitHub Action that auto-posts an AI code review comment whenever a PR is opened.

**Stack:** GitHub Actions + Claude API | **Build time:** ~1–2 hours | **Folder:** [`pr-review-bot/`](./pr-review-bot/)

### 4. Dead Link Checker
Give it a URL or markdown file, it crawls all links and reports broken ones.

**Stack:** Python + httpx + asyncio | **Build time:** ~1–2 hours | **Folder:** [`dead-link-checker/`](./dead-link-checker/)

### 5. ENV Diff Tool
Compares `.env.example` against `.env` and shows what's missing, extra, or mismatched.

**Stack:** Python or Go, zero dependencies | **Build time:** ~1 hour | **Folder:** [`env-diff/`](./env-diff/)

## Getting Started

Each folder contains its own README with setup instructions. Pick a project and start building!
