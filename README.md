<div align="center">

# ⚡ espanso triggers

**A single source of truth for all my text expansion snippets — synced everywhere via `git pull`.**

[![espanso](https://img.shields.io/badge/espanso-text%20expansion-7C3AED?style=for-the-badge&logo=lightning&logoColor=white)](https://espanso.org)
[![YAML](https://img.shields.io/badge/YAML-powered-F5A623?style=for-the-badge&logo=yaml&logoColor=white)](https://yaml.org)
[![Sync](https://img.shields.io/badge/sync-git%20pull-0F80C1?style=for-the-badge&logo=git&logoColor=white)](https://git-scm.com)
[![Maintained](https://img.shields.io/badge/maintained-yes-22C55E?style=for-the-badge)](.)

</div>

---

## What is this?

[Espanso](https://espanso.org) is a cross-platform text expander. Type a short trigger anywhere on your system and it instantly replaces it with your defined snippet — commands, signatures, dynamic values, you name it.

This repo lives at `espanso/match/` on every device I use. A single `git pull` keeps all machines perfectly in sync, no manual copying required.

---

## How to sync

```bash
# Navigate to your espanso match directory
cd $(espanso path) # or wherever your match folder lives

# Pull the latest triggers
git pull origin main
```

That's it. Espanso picks up changes automatically.

---

## Trigger Reference

### 🛠️ DevOps

| Trigger | Output |
|---|---|
| `:date` | Current date (`MM/DD/YYYY`) |
| `:myip` | Your current public IP address |
| `:branch` | Current git branch name |
| `:clog` | `console.log('DEBUG \| $\|$');` |
| `:espanwd` | Path to this espanso match directory |

### 🪪 Personal Brand

| Trigger | Output |
|---|---|
| `:email` | Primary email address |
| `:sig` | Full professional email signature |
| `:dom` | Primary domain URL |

---

## Adding New Triggers

Edit `base.yml` (or create a new `.yml` file in this directory) following the [espanso match syntax](https://espanso.org/docs/matches/basics/), then commit and push. All other devices stay current with a `git pull`.

---

<div align="center">

## 👋 Let's connect

I'm **coffeycodes** — a developer, solutions architect, and digital creator.  
Find my projects, socials, and everything else in one place:

### 🌿 [linktr.ee/coffeycodes](https://linktr.ee/coffeycodes)

</div>
