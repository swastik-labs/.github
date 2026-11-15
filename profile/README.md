<div align="center">

# 🖥️ Swastik Labs

**My home server lab: self-hosted bots, services, and experiments.**

Everything here runs on an old laptop at home, deployed via self-hosted GitHub Actions runners.

![Hardware](https://img.shields.io/badge/server-Lenovo%20i3%2012th%20gen-orange?style=flat&logo=lenovo&logoColor=white)
![OS](https://img.shields.io/badge/OS-Ubuntu-E95420?style=flat&logo=ubuntu&logoColor=white)
![Docker](https://img.shields.io/badge/runs%20on-Docker-2496ED?style=flat&logo=docker&logoColor=white)
![CI](https://img.shields.io/badge/CI-self--hosted%20runners-2ea44f?style=flat&logo=githubactions&logoColor=white)

</div>

---

## 🤖 What's Running

> Deploy badges update every 30 minutes from each repo's latest deploy on `main`.

### 🌐 Web apps

| Project | What it does | Stack | Status |
| --- | --- | --- | --- |
| 🎒 **Bunkers** | Attendance calculator: how many classes you can skip and still stay above your target | Vite · JS · Docker | ![deploy](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fswastik-labs%2F.github%2Fmain%2Fbadges%2Fbunkers.json) |
| 💊 **Medical Tracker** | Phone-friendly tracker for medication doses and test results | FastAPI · SQLite | ![deploy](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fswastik-labs%2F.github%2Fmain%2Fbadges%2Fmedical-tracker.json) |

### 🤖 Bots

| Project | What it does | Stack | Status |
| --- | --- | --- | --- |
| 🛡️ **DefenderBot** | Discord community bot: moderation, automod, XP levels, tickets, giveaways | discord.py · Supabase | ![deploy](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fswastik-labs%2F.github%2Fmain%2Fbadges%2Fpvt-discordbot.json) |
| ⛏️ **Minecraft Bot** | Discord bot for the Minecraft server | Python · Docker | ![deploy](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fswastik-labs%2F.github%2Fmain%2Fbadges%2Fpvt-minecraft-bot.json) |

### 🛠️ Infrastructure

| Project | What it does | Stack | Status |
| --- | --- | --- | --- |
| 📊 **Homelab Dashboard** | "Is everything OK?" dashboard for the server, with plain-English stats | Python · Docker | ![deploy](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fswastik-labs%2F.github%2Fmain%2Fbadges%2Fhomelab-main.json) |
| 🎮 **MC Panel** | Self-hosted, Aternos-style Minecraft server manager | FastAPI · Docker SDK · Alpine.js | ![deploy](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fswastik-labs%2F.github%2Fmain%2Fbadges%2Fmcpannel.json) |

## ⚙️ How It Works

```
push to repo  →  GitHub Actions  →  self-hosted runner (old laptop 💻)  →  docker compose up 🐳  →  live 🚀
```

- 💻 **Hardware:** Lenovo laptop, Intel Core i3 (12th gen), repurposed as a home server
- 🐧 **OS:** Ubuntu
- 🐳 **Stack:** every service runs in its own Docker container
- 🔁 **Deploys:** automatic on push to `main`, each followed by a health check

## 📂 Repos

- Most repos are private 🔒 because they hold server config, but their deploy status is public above
- Public repos are open for anyone to use or learn from

## 🤝 Contributing

Issues and ideas are welcome on any public repo.

<div align="center">
<sub>Built and hosted at home on an old laptop ⚡</sub>
</div>
