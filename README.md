<div align="center">

<!-- HERO BANNER -->
<a href="https://github.com/RakeshRautDev">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1e3a8a,100:2563eb&height=240&section=header&text=Rakesh%20Raut&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=Software%20Engineer%20%7C%20Full-Stack%20%7C%20AI%2FML%20%7C%20Systems%20%26%20Networking&descAlignY=60&descSize=18&animation=fadeIn" width="100%" />
</a>

<a href="https://github.com/RakeshRautDev">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1000&color=2563EB&center=true&vCenter=true&width=850&lines=Building+real-world+software%2C+not+just+demos;7+shipped+projects+%E2%80%94+AI%2FML%2C+Android%2C+Networking%2C+GIS;Three+of+them+solve+real+problems+for+India" />
</a>

<br/>

<a href="https://github.com/RakeshRautDev">
  <img src="https://komarev.com/ghpvc/?username=RakeshRautDev&label=Profile%20Views&color=2563eb&style=for-the-badge" />
</a>
<a href="https://github.com/RakeshRautDev?tab=followers">
  <img src="https://img.shields.io/github/followers/RakeshRautDev?label=Followers&style=for-the-badge&color=1e3a8a" />
</a>
<a href="https://github.com/RakeshRautDev?tab=repositories">
  <img src="https://img.shields.io/badge/Public%20Repos-48-2563eb?style=for-the-badge" />
</a>

</div>

---

## 👋 About Me

I'm **Rakesh Raut**, a Computer Science engineer who prefers finishing things over demoing them. Across my repos there's a pattern: I pick a real, specific problem — a slow document workflow at a local Common Service Centre, the opacity of Indian electoral data, a phone stuck in a drawer that could be a keyboard — and build the *whole* thing: backend, frontend, packaging, and (usually) a working deployment.

Three of my projects independently ended up solving the same kind of problem — **making Indian civic and administrative data usable** — without me setting out to build a "suite":

- 🇮🇳 **[NetaKhoj](https://github.com/RakeshRautDev/NetaKhoj)** maps all 543 Parliamentary + 4,120+ Assembly constituencies to their representatives
- 🗺️ **[CivicSpatial API](https://github.com/RakeshRautDev/CivicSpatial-API)** turns any GPS coordinate into jurisdiction, ward, and representative data
- 📄 **[JSK PDF Suite](https://github.com/RakeshRautDev/JSK-PDF-Suite)** is a desktop toolkit built specifically for Jan Seva Kendra (CSC) operators

Alongside that, I dig into **applied AI/ML research** (a hybrid deepfake + misinformation detector benchmarked at 94.8% accuracy), **low-level Android** (spoofing a Bluetooth HID keyboard profile), and **networking internals** (a live DNS/TLS/traceroute dashboard).

> **My approach:** find an interesting, real problem, understand it deeply, and turn it into working software — not a proof of concept.

---

## 🛠️ Tech Stack

**Languages**
<p align="center">
<img src="https://skillicons.dev/icons?i=python,javascript,java,kotlin,html,css" />
</p>

**Backend, Frontend & Data**
<p align="center">
<img src="https://skillicons.dev/icons?i=nodejs,express,react,firebase,appwrite,fastapi,vite,tailwind" />
</p>

**AI / ML**
<p align="center">

`PyTorch` • `Transformers` (`RoBERTa` · `DeBERTa-v3` · `CLIP`) • `LoRA` • `Gradio` • `Hugging Face Hub` • `Google Gemini`

</p>

**Geospatial, Networking & Systems**
<p align="center">

`Turf.js` • `Leaflet.js` • `satellite.js (SGP4)` • `Three.js` • `WebSockets` • `PyMuPDF`

</p>

**Cloud, DevOps & Tools**
<p align="center">
<img src="https://skillicons.dev/icons?i=docker,vercel,git,github,androidstudio,vscode" />
</p>

---

## ⭐ Featured Projects

A closer look at the seven projects I'd actually point you to — pulled straight from each repo's own README.

### 🛡️ [VeriDex](https://github.com/RakeshRautDev/VeriDex) — Hybrid Misinformation & Deepfake Forensics System

Three independently-trained pipelines — a fine-tuned RoBERTa text-deception classifier, a DeBERTa-v3 evidence-retrieval stance model with credibility-weighted web search, and a CLIP + frequency-domain deepfake image detector — combined through an empirically-derived 40/60 "Hybrid Resolution Engine." On a custom 500-claim adversarial benchmark it reports **94.8% accuracy** and a **0.965 AUC-ROC**, beating FakeBERT by +4.8pp.

`Python` `PyTorch` `RoBERTa` `DeBERTa-v3` `CLIP + LoRA` `Gradio`
[Live Demo (Hugging Face Space)](https://huggingface.co/spaces/rex177/VeriDex) · [Repo](https://github.com/RakeshRautDev/VeriDex)

---

### 🇮🇳 [NetaKhoj](https://github.com/RakeshRautDev/NetaKhoj) — India's Electoral Intelligence Platform

An interactive Leaflet.js map of every Lok Sabha and Vidhan Sabha constituency in India, backed by an Express/Node.js API with a custom-built security layer (pattern-matching threat detection, automatic IP blocking, rate limiting) and Puppeteer/Cheerio scrapers that keep representative data current — all synced live to connected clients over WebSockets.

`Node.js` `Express` `Appwrite` `WebSockets` `Leaflet.js` `Docker`
[Live Demo](https://netakhoj-web.vercel.app/) · [Repo](https://github.com/RakeshRautDev/NetaKhoj)

---

### 📄 [JSK PDF Suite](https://github.com/RakeshRautDev/JSK-PDF-Suite) — Desktop Toolkit for CSC Operators

Built for the specific, repetitive pain points of Indian Jan Seva Kendra / cyber-café operators: a visual point-and-click PDF page editor, an "Exact-KB" image compressor (binary-searches JPEG quality to hit a target file size — useful for Aadhaar/PAN upload limits), an Aadhaar/PAN-to-A4 combiner, and click-to-redact tooling. Ships as a standalone `.exe`.

`Python` `CustomTkinter` `PyMuPDF` `PDFPlumber` `PyInstaller`
[Repo](https://github.com/RakeshRautDev/JSK-PDF-Suite)

---

### 🌐 [NetTracer](https://github.com/RakeshRautDev/NetTracer) — Live Network Intelligence Dashboard

Traces a URL's full path across the internet in real time over a WebSocket stream: DNS records, TLS certificate/cipher details, WHOIS data, CDN fingerprinting, and a hop-by-hop UDP traceroute with reverse-DNS, ASN, and geo-location per router (falling back to the system `traceroute`/`tracert` when raw sockets aren't available).

`Python` `FastAPI` `WebSockets` `DNS/TLS/WHOIS`
[Repo](https://github.com/RakeshRautDev/NetTracer)

---

### ⌨️ [MorphKeys](https://github.com/RakeshRautDev/MorphKeys) — Android Phone → Bluetooth HID Keyboard

Turns an Android phone into a hardware-emulated Bluetooth keyboard using the native `BluetoothHidDevice` API — no receiver app needed on the host. Includes a human-behavior typing engine (Gaussian keystroke jitter, configurable WPM, optional realistic typo-and-backspace simulation) and an "IDE mode" that strips auto-indent noise when pasting code into an editor.

`Kotlin` `Jetpack Compose` `Bluetooth HID`
[APK Download](https://github.com/RakeshRautDev/MorphKeys/blob/main/MorphKeys.apk) · [Repo](https://github.com/RakeshRautDev/MorphKeys)

---

### 🗺️ [CivicSpatial API](https://github.com/RakeshRautDev/CivicSpatial-API) — Geospatial Civic-Intelligence API

Give it a latitude/longitude and it resolves administrative jurisdiction, municipal ward, nearest infrastructure (police stations, highways, railways), and elected MP/MLA — enriched with Wikipedia summaries. Built as independent serverless functions on Vercel using Turf.js for the geometry.

`Node.js` `Express` `Turf.js` `Vercel Serverless`
[Live API](https://represetative.vercel.app/api/electoral?lat=19.0760&lon=72.8777) · [Repo](https://github.com/RakeshRautDev/CivicSpatial-API)

---

### 🛰️ [Orbital Command](https://github.com/RakeshRautDev/Orbital-Command) — Real-Time Satellite & Solar System Tracker

A 3D visualization tracking **15,000+ satellites and debris objects** via live TLE data from Celestrak, propagated with SGP4 (`satellite.js`) for exact real-time positions. Also renders a heliocentric solar system with 8K planet textures, live NASA EPIC Earth imagery, ISS tracking, and automatic conjunction (close-approach) detection between tracked objects.

`React 19` `Three.js` `@react-three/fiber` `satellite.js` `Zustand`
[Live Demo](https://space-debris-tracker.vercel.app/) · [Repo](https://github.com/RakeshRautDev/Orbital-Command)

---

<details>
<summary><b>💊 Also worth a look: SmartMed — AI-Powered Healthcare Assistant</b> (Gemini-based symptom checker, forked 3×)</summary>
<br>

An earlier full-stack project: an AI symptom checker (text, image, and voice input) built on the Gemini API, generating personalized medical plans and exportable synthetic patient records — with Firebase handling auth and data. It's picked up 3 forks, the most of any repo on my profile.

`Firebase` `Google Gemini API` `JavaScript`
[Repo](https://github.com/RakeshRautDev/SmartMed)

</details>

---

## 📊 GitHub Stats

<div align="center">
<a href="https://github.com/RakeshRautDev">
  <img height="180" src="https://github-readme-stats.vercel.app/api?username=RakeshRautDev&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&rank_icon=github" />
  <img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=RakeshRautDev&layout=compact&langs_count=10&hide_border=true" />
</a>
</div>

## 🔥 Contribution Streak

<div align="center">
<img src="https://streak-stats.demolab.com?user=RakeshRautDev&hide_border=true" />
</div>

## 🏆 GitHub Trophies

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=RakeshRautDev&theme=flat&no-frame=true&no-bg=true&margin-w=8&row=1" />
</div>

---

## 💻 Coding Profiles

<div align="center">

<a href="https://leetcode.com/u/54iQWHXri5/">
  <img src="https://img.shields.io/badge/LeetCode-54iQWHXri5-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" />
</a>
<a href="https://www.geeksforgeeks.org/profile/iamrakep8vx">
  <img src="https://img.shields.io/badge/GeeksforGeeks-iamrakep8vx-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white" />
</a>

</div>
<br/>
<div align="center">
<a href="https://leetcode.com/u/54iQWHXri5/">
  <img src="https://leetcard.jacoblin.cool/54iQWHXri5?theme=dark&font=baloo&ext=heatmap" width="500" />
</a>
</div>

---

## 🧩 What I'm Currently Exploring

```text
AI / ML Research          ████████████████████████░
Full-Stack Engineering    █████████████████████████
Systems & Networking      ███████████████████████░░
Android (Kotlin/Compose)  ████████████████████░░░░░
GIS & Spatial Computing   ███████████████████░░░░░░
Developer Tooling         █████████████████████░░░░
```

---

## 🌍 Connect With Me

<div align="center">

<a href="https://github.com/RakeshRautDev">
  <img src="https://img.shields.io/badge/GitHub-RakeshRautDev-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>
<a href="https://www.linkedin.com/in/rakeshkumarraut/">
  <img src="https://img.shields.io/badge/LinkedIn-Rakesh%20Kumar%20Raut-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="https://leetcode.com/u/54iQWHXri5/">
  <img src="https://img.shields.io/badge/LeetCode-Profile-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" />
</a>
<a href="https://www.geeksforgeeks.org/profile/iamrakep8vx">
  <img src="https://img.shields.io/badge/GeeksforGeeks-Profile-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white" />
</a>

</div>

---

<div align="center">

### ⚡ Build. Break. Learn. Repeat.

**Thanks for stopping by — go star something in the list above 👆**

<a href="https://github.com/RakeshRautDev">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2563eb,50:1e3a8a,100:0f172a&height=120&section=footer" width="100%" />
</a>

</div>
