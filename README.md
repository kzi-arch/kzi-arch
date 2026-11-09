# KZI

Security engineering and full-stack development. Arch Linux daily driver.

[zakiaddaroni9@gmail.com](mailto:zakiaddaroni9@gmail.com) · [LinkedIn](https://linkedin.com/in/zaki-addaroni-906850340) · [TryHackMe](https://tryhackme.com/p/Kzi)

---

## What I do

Two things, usually in the same week.

The first is reading other people's request handlers — looking for the spot where
the validation doesn't quite match the documentation, or where the parameter
that was never meant to be user-controlled turns out to be. Web apps, APIs,
mostly. Burp open, proxy on, patience required.

The second is writing the backend that doesn't have those spots. Laravel or
Node, depending on what the project already uses. Threat model first, queries
parameterised from the start, permissions set to the minimum that still works.

The two feed each other. You don't write a hardened service until you've spent
time taking one apart.

---

## Repositories

| | |
| :-- | :-- |
| [**fumi**](https://github.com/kzi-arch/fumi) | Fork of [imaaiagent/fumi](https://github.com/imaaiagent/fumi) — AI desk companion on ESP32-S3. Kept here as a working copy while I port it to my board |
| [**purplescan**](https://github.com/kzi-arch/purplescan) | Reconnaissance and vulnerability scanning for web targets |
| [**empathai-chatbot**](https://github.com/kzi-arch/empathai) | Conversational agent. Most of the actual work went into context handling and keeping the guardrails honest on sensitive topics |
| [**media-bot**](https://github.com/kzi-arch/media-bot) | Media resolver bot. Built around rate limits and upstreams that fail at the worst possible moment |
| [**Lumora-website**](https://github.com/kzi-arch/Lumora-website) | Front-end build. Layout, motion, responsive behaviour, no framework in the way |

---

## Certifications

In order, because the order matters more than the list:

**eJPT** — in progress. Networking, enumeration, exploitation methodology.
The practical baseline before anything gets specialised.

**CompTIA Security+** — aiming for late 2026. Threats, architecture, operations,
governance. Less exciting than the offensive track and more useful than people
admit — it's the vocabulary that makes security legible to the rest of the team.

**OSCP** — after that. 24-hour hands-on exam. The one that actually means
something on the offensive side.

Practice happens on HackTheBox, TryHackMe, and PortSwigger's Web Security
Academy. Write-ups go up once a box retires.

---

## Tooling

**Languages** — Python, JavaScript, Bash, PHP, SQL, plus enough C++ to read a
stack trace without panic

**Frameworks** — Laravel, Node.js, Express, React

**Security** — Burp Suite, Nmap, Wireshark, Metasploit, GDB

**Everything else** — Arch Linux, Docker, Git, neovim, tmux

<details>
<summary>Why Arch, and other questions nobody asked</summary>

<br>

**Arch** because I broke it once in the first month and had to learn how it fit
together to fix it. That turned out to be the point. Rolling release also means
the security tooling is never a version behind.

**neovim + tmux + zsh** because switching between a terminal and an editor is a
context switch, and context switches cost more than the setup ever did.

**Burp over the alternatives** because the Repeater workflow matches how I think:
one request, change one thing, look at what came back.

**KISS**, applied to security. The complicated solution has more places to be
wrong. The boring solution you understand completely is usually the safer one.

</details>

---

## Currently

Working through PortSwigger's labs, chipping away at eJPT material, and slowly
turning the self-hosted lab into something worth documenting.

Open to security engineering and full-stack roles. If you want to talk about a
project, an opportunity, or a finding you're not sure how to report — email works
best.

<p align="center">
  <img height="140" src="https://github-readme-stats.vercel.app/api?username=kzi-arch&show_icons=true&hide_title=true&hide_border=true&hide=issues&theme=transparent" alt="GitHub stats" />
</p>
