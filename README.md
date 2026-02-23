
# GRIM - Tabletop Simulator Mod

Official automation and scripting system for the GRIM TCG inside Tabletop Simulator.

This project aims to create a fully playable, automated, and scalable digital tabletop version of GRIM, including combat, effects, UI, and card systems.

---

## ⚠️ Disclaimer

This project is developed with the assistance of AI tools to accelerate design, scripting, system architecture, and workflow optimization.  
All game design, balance, direction, and final implementation decisions remain human-led.

AI is used strictly as a development aid to:
- Speed up scripting and automation
- Assist with system design and scalability
- Improve workflow and testing efficiency
- Help document and organize the project

This allows the GRIM project to grow faster while maintaining full creative control and ownership.

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
```

TYPE=GRIM
NAME=...
ELEMENT=...
SPEED=...
HP=...
START_STAMINA=...

```

---

### Full Recommended Format
```

TYPE=GRIM
NAME=...
ELEMENT=...
SPEED=...
HP=...
START_STAMINA=...

ATK1_NAME=...
ATK1_DMG=...
ATK1_EFFECT=...

ATK2_NAME=...
ATK2_DMG=...
ATK2_EFFECT=...

PASSIVE=...
PASSIVE2=...

```

This allows the automation system to:
- Read card stats
- Apply damage
- Trigger effects
- Scale future mechanics

---

## 🎮 Systems Roadmap

### Phase 1 (Current)
- GM Notes database
- Grim selection
- UI control panel
- Attack system base

### Phase 2
- Turn system
- Stamina tracking
- Speed order
- Status effects

### Phase 3
- Effect engine
- Limbo / Afterworld automation
- Targeting system

### Phase 4
- Multiplayer sync
- Match flow automation
- Reaction timing

### Phase 5
- Expansions
- Custom decks
- Ranked play support

---

## 💡 Contribution
This project is open to collaboration and future development.

---

## 📜 License
MIT
```

---
