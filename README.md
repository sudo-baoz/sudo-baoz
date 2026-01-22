<div align="center">

  <img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="100%" height="150" style="object-fit: cover;" />

  <h1 align="center">🔓 sudo-baoz (Mai Quốc Bảo)</h1>

  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=24&duration=3000&pause=1000&color=00FF00&center=true&vCenter=true&width=600&lines=uid%3D0(root)+gid%3D0(root)+groups%3D0(root);Exec:+/bin/sh+-c+pwn_the_world.py;Target:+HUTECH+Information+Security;Status:+Bypassing+DEP%2FNX..." alt="Typing SVG" />
  </a>

  <br/>

  <a href="https://ctftime.org/team/412747">
    <img src="https://img.shields.io/badge/CTF_Time-Team_ID:_412747-DC143C?style=for-the-badge&logo=target&logoColor=white" />
  </a>
  <a href="https://github.com/sudo-baoz">
    <img src="https://img.shields.io/badge/GitHub-sudo--baoz-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="mailto:your-email@example.com">
    <img src="https://img.shields.io/badge/ProtonMail-Encrypted-6D4AFF?style=for-the-badge&logo=protonmail&logoColor=white" />
  </a>

</div>

<br/>

### 📟 **`cat /etc/motd`**

> *"Everything is a file. If it's not a file, it's a process. If it's not a process, it's a flag waiting to be captured."*

Yo! 👋 I'm **Mai Quốc Bảo**, a first-year student @ **HUTECH**.
My terminal is my home, and **Arch Linux** is my weapon of choice. I spend my nights analyzing binaries, crafting exploits, and automating the boring stuff.

* 🔭 **Main Quest:** Mastering **Binary Exploitation (Pwn)** & **Reverse Engineering**.
* 🛡️ **Side Quest:** Web Security & Forensics.
* ⚙️ **Environment:** Arch Linux (Hyprland) | Vim enthusiast (I know how to exit, promise).
* ⚡ **Current Status:** Learning Heap Exploitation & Kernel Pwn.

---

### 🛠️ **Inventory (`dpkg --list`)**

| **Exploit Dev** | **Scripting & Automation** | **Infrastructure & OS** |
| :---: | :---: | :---: |
| <img src="https://skillicons.dev/icons?i=c,cpp,assembly,rust" /> | <img src="https://skillicons.dev/icons?i=python,bash,nodejs,git" /> | <img src="https://skillicons.dev/icons?i=arch,linux,docker,kali" /> |
| *Buffers won't overflow themselves* | *Automate or die trying* | *I use Arch btw* |

---

### 🏆 **CTF Scoreboard (`/var/log/ctf.log`)**

| **Event** | **Rank** | **Points** | **Status** |
| :--- | :---: | :---: | :---: |
| 🏰 **The Maze of Shadows** | **#3** | `4559` | 👑 LEGENDARY |
| 🇦🇷 **Metared Argentina 2025** | **#83** | `2300` | 🔥 HEATING UP |
| 🤖 **M*CTF 2025 Quals** | **#92** | `201.000` | 🧠 BIG BRAIN |
| 🧊 **GlacierCTF 2025** | **#136** | `450.000` | 💀 GRINDING |

---

### 📊 **Github Analytics**

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=sudo-baoz&show_icons=true&theme=tokyonight&hide_border=true&bg_color=000000&title_color=00FF00&icon_color=00FF00" height="150" alt="stats graph" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sudo-baoz&layout=compact&theme=tokyonight&hide_border=true&bg_color=000000&title_color=00FF00&icon_color=00FF00" height="150" alt="languages graph" />
</div>

---

### 💻 **`vim exploit.py`**

```python
#!/usr/bin/env python3
from pwn import *

# Author: sudo-baoz
# Mission: Get Root or Die Trying

context.arch = 'amd64'
context.log_level = 'debug'

def daily_routine():
    target = ELF('./university_life')
    baoz = process('./sudo-baoz')

    # The buffer is just a suggestion
    payload  = b"A" * 8              # Sleep(8)
    payload += p64(0xcAfEBb)         # Coffee()
    payload += asm(shellcraft.sh())  # Spawning a shell... I mean, study session

    try:
        baoz.sendline(payload)
        baoz.interactive()
    except EOFError:
        log.critical("Segfault! Pivot to Web Security...")

if __name__ == "__main__":
    daily_routine()

```

<div align="center">





<img src="https://www.google.com/search?q=https://komarev.com/ghpvc/%3Fusername%3Dsudo-baoz%26style%3Dflat-square%26color%3D00FF00%26label%3DVISITORS" alt="visitors" />
</div>
