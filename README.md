# 📦 MetaMatch: Ranked Draft Assistant (Mythic Tier+)

**MetaMatch** is a full-stack, esports-grade Brawl Stars Ranked Draft Simulator. Built with **Bolt (React + TypeScript)** and powered by **Supabase**, this tool replicates the full ranked experience from configuration to evaluation.

---

## 🌐 Live Demo
Coming soon: [MetaMatch Draft Simulator](https://metamatch.app)

---

## ⚙️ Tech Stack

| Layer          | Tech Used                |
|----------------|--------------------------|
| Frontend       | React + TypeScript (Bolt) |
| Backend        | Supabase (PostgreSQL + Auth) |
| Deployment     | Vercel                   |
| Data Storage   | localStorage, Supabase DB|
| UI Components  | Tailwind + ShadCN        |
| Images         | Brawlify CDN             |

---

## 🧩 Features
- 🔐 Account Linking (via Player Tag)
- 🎮 Full Ranked Simulation (6 Phases)
- 🤖 Practice Draft Mode (manual)
- 🧠 AI Coach Feedback Panel
- 📚 Strategy Tips Sidebar
- 🔍 Matchup Explorer
- 💾 Career Tracker (local)
- 📊 Dynamic Win Probability
- 📸 Export Draft Image
- 🌀 Chaos Mode (optional)
- 🧱 Ranked Rules Reference Panel

---

## 🧠 App Flow

```text
1️⃣ CONFIGURATION PHASE  
2️⃣ MODE & MAP SELECTION  
3️⃣ ORDERING (Coin Toss)  
4️⃣ BAN PHASE  
5️⃣ DRAFT PHASE  
6️⃣ EVALUATION PHASE  
+ CoachFeedback, Export, CareerStats
```

---

## 🗂️ Folder Structure

```bash
/src
  ├── api/               # Supabase + Brawl API logic
  ├── components/        # All UI components (Phases, Sidebar, Coach, etc)
  ├── data/              # JSON data: brawlers, strategyTips, elo_rules
  ├── utils/             # draftLogic, storage helpers
  ├── App.tsx            # Main app entry
  ├── main.tsx           # Bootstrap
/public
  ├── logo-symbol.png    # Brand icon
/docs
  ├── architecture.png   # MetaMatch full-stack architecture
  ├── draft_phases.png   # Simulation phase flow
  ├── features.md        # Feature breakdown
/vercel.json             # Deployment config
/supabase.config.json    # DB setup script
.gitignore
.editorconfig
meta.json                # Project metadata
```

---

## 🚀 Deployment

```bash
# Dev
npm install
npm run dev

# Build
npm run build
```

---

## 🛠️ Contributing

```bash
# Clone the repo
https://github.com/waders001/metamatch.git

# Feature branches
feature/phase3-bot-mode
feature/rules-panel
```

Please see `/docs/features.md` and `/docs/architecture.png` before submitting PRs.

---

## 📜 License
MIT License
