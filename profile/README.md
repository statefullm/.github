# LIM Coding Assistant

**Building tools for local, stateful AI inference.**

## Projects

### [LIM](https://github.com/statefullm/lim) — Local Inference Manager

A C++ terminal-based LLM controller with persistent KV-cache, native filesystem tools, and instant undo. Built on [llama.cpp](https://github.com/ggml-org/llama.cpp).

**Key features:**
- **Stateful sessions** — KV-cache is never discarded. No re-tokenization or re-decode overhead per turn.
- **Native tools** — Read, search, edit, and write files; run shell commands; search the web; read PDFs.
- **Session save/restore** — Save full session state and restore later with zero context loss.
- **Interactive undo** — Rewind to any checkpoint in your session history.
- **Browser output** — LaTeX-aware viewer streamed via WebSocket.
- **VS Code extension** — Integrated terminal and browser workspace.

