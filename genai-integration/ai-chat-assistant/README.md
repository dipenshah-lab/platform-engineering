# Chat Assistant

A lightweight internal chat assistant powered by OpenAI's latest models, designed for daily use with persistent context, session history, and project continuity.

---

## Current Features

- ✅ Jupyter-based UI with `ipywidgets` for intuitive chat
- ✅ Supports GPT-4 / GPT-4o via OpenAI API
- ✅ Auto-saves chat history as JSON by session ID
- ✅ Persistent context within each session
- ✅ Markdown-rendered messages for clean formatting

---

## Planned Features & UI Enhancements

- 🔄 **Session Resumption** — Reopen and continue past conversations
- 🧠 **Project Memory** — Group chats by topic or project for richer recall
- 🔍 **Searchable History** — Quick lookup across saved sessions
- 🗂 **Session Selector** — Dropdown to switch between chat threads
- 🧾 **Transcript Export** — Save full sessions to `.md` or `.txt`
- 🎨 **Custom Styling** — More ChatGPT-like message bubbles and timestamps
- 🧪 **API Playground Mode** — Inline tweaks for temperature, top_p, etc.
- 📦 **Docker / Binder Support** — Run anywhere with minimal setup

---

## Env Setup

Ensure the following are set in `.env`:

```dotenv
OPENAI_API_KEY=your-key-here
OPENAI_MODEL=gpt-4o
