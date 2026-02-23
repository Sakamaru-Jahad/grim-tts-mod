# GRIM - Tabletop Simulator Mod

Official automation and scripting system for the GRIM TCG inside Tabletop Simulator.

This project aims to create a fully playable, automated, and scalable digital tabletop version of GRIM, including combat, effects, UI, and card systems.

---

## 🚀 Goals
- Fast and smooth gameplay
- Minimal manual bookkeeping
- Scalable card database
- Modular scripting system
- Future expansion support
- Competitive and casual play ready

---

## 🛠 Tools & Stack
- Tabletop Simulator
- Lua scripting (TTS API)
- TTS XML UI
- Cursor (primary editor)
- GitHub (version control)
- GM Notes database system

---

## 📂 Dev Workflow
1. Edit `Global.lua` in Cursor
2. Copy into **TTS → Scripting → Global**
3. Test inside Tabletop Simulator
4. Save only when stable
5. Commit changes to GitHub

⚠️ Always overwrite your save before testing new scripts.

---

## 📊 Card Database (GM Notes)

Cards use a structured KEY=VALUE format stored in GM Notes.

### Minimum Required
