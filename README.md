# 🟦 Nebunix XMonad Edition

**Minimal. Reproducible. Hardcore.**

![NixOS](https://img.shields.io/badge/NixOS-unstable-blue?style=flat-square&logo=nixos)
![XMonad](https://img.shields.io/badge/XMonad-tiling%20wm-purple?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)
![Status](https://img.shields.io/badge/Status-Active-success?style=flat-square)
![Powerlevel10k](https://img.shields.io/badge/Zsh-Powerlevel10k-orange?style=flat-square)
![GitHub stars](https://img.shields.io/github/stars/nebunix/nebunix-xmonad-edition?style=flat-square)



------------------------------------------------------------------------

# 🌍 ENGLISH

## 💥 What is Nebunix XMonad Edition?

Nebunix XMonad Edition is a fully reproducible, no-bloat,
keyboard-driven power-user desktop built on:

-   NixOS\
-   XMonad\
-   Zsh + Powerlevel10k\
-   Performance-first philosophy

This is not a beginner OS.\
This is a nerd-grade daily driver for:

-   Developers\
-   Homelab administrators\
-   Linux power users\
-   Tiling WM addicts\
-   Reproducibility fanatics

It is the hardcore counterpart to Project Maxwell, which targets
beginners and Windows users.

------------------------------------------------------------------------

## 🧠 Core Philosophy

"No clutter. No guessing. No mouse dependency. Only control."

------------------------------------------------------------------------

## 🗂️ Repository Structure

<pre>
nebunix-xmonad-edition/
├── configuration.nix
├── hardware/
│   └── hardware-example.nix
├── profiles/
│   ├── base-system.nix
│   ├── desktop-xmonad.nix
│   ├── shell-zsh.nix
│   ├── users.nix
│   ├── networking.nix
│   ├── gaming.nix
│   └── services.nix
├── dotfiles/
│   ├── xmonad/
│   ├── polybar/
│   ├── fastfetch/
│   └── zsh/
├── scripts/
│   ├── install.sh
│   └── rebuild.sh
├── screenshots/
│   └── desktop.png
└── README.md
</pre>


---

## 🔄 Reproducibility Workflow

1. Live system runs stable  
2. Config is mirrored to GitHub  
3. Reproduction is tested on a trash SSD  
4. Only then deployed to production NVMe  

This guarantees:
- Zero fear rebuilds  
- No accidental system wipes  
- Hardware-independent recovery  

---

## ⚙️ Installation (Advanced Users Only)

> This assumes you already installed NixOS.

```bash
git clone https://github.com/nebunix/nebunix-xmonad-edition /etc/nixos
cd /etc/nixos
nixos-generate-config
nixos-rebuild switch

Replace the hardware file inside:
hardware/
with your own:
hardware-your-machine.nix
```

## 🧙 Target Audience

✅ You will love this if you:

Use Tiling WMs

Hate Desktop Bloat

Love Declarative Systems

Rebuild your OS for fun

Live in the terminal

Care about reproducibility

❌ You will NOT like this if you:

Want click-only workflows

Fear config files

Expect GUI control panels

Want a Windows clone

⚠️ Disclaimer

This is a power-user OS configuration.
No warranties. No hand holding. No mercy.
Use at your own risk.

---


# 🇩🇪 DEUTSCH

## 💥 Was ist die Nebunix XMonad Edition?

Die **Nebunix XMonad Edition** ist ein **vollständig reproduzierbares, pures, tastatur Power-User-Desktop-System** auf Basis von:

- **NixOS**
- **XMonad**
- **Zsh + Powerlevel10k**
- **Performance-First-Philosophie**

Dies ist **kein Einsteiger-System**.  
Dies ist ein **Nerd-Daily-Driver** für:

- Entwickler
- Homelab-Admins
- Linux-Power-User
- Tiling-WM-Fans
- Reproduzierbarkeits-Enthusiasten

Es ist das **Hardcore-Gegenstück** zu **Project Maxwell** für Einsteiger.

---

## 🧠 Philosophie

> „Kein Ballast. Keine Maus-Abhängigkeit. Nur Kontrolle.“

- ✅ Deklarative Systemkonfiguration  
- ✅ Vollständig reproduzierbar  
- ✅ Kein Desktop-Bloat  
- ✅ Tastatur-zentrierter Workflow  
- ✅ Modulare NixOS-Profile  
- ✅ GitHub-Desktop als Infrastruktur  

---

## 🚀 Features

- 🔁 **100 % reproduzierbar**
- 🧩 **Modulares System**
- 🎮 **Gaming-ready**
- 🔐 **Sicheres Rebuild & Rollback**
- 🧠 **Nerd-optimierte Shell**
- 💣 **Für Daily-Use und Experimente**
  
## 🗂️ Repository Structure

<pre>
nebunix-xmonad-edition/
├── configuration.nix
├── hardware/
│   └── hardware-example.nix
├── profiles/
│   ├── base-system.nix
│   ├── desktop-xmonad.nix
│   ├── shell-zsh.nix
│   ├── users.nix
│   ├── networking.nix
│   ├── gaming.nix
│   └── services.nix
├── dotfiles/
│   ├── xmonad/
│   ├── polybar/
│   ├── fastfetch/
│   └── zsh/
├── scripts/
│   ├── install.sh
│   └── rebuild.sh
├── screenshots/
│   └── desktop.png
└── README.md
</pre>


⚠️ Haftungsausschluss

Power-User-System.
Keine Garantie. Kein Händchenhalten ;)
Benutzung auf eigene Gefahr. 
