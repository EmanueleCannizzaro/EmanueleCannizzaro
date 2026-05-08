### :wave: Hello 👋

my name is Emanuele Cannizzaro 

I'm an engineer and CTO. I run the technical side of [AECS4U](https://aecs4u.it), where
we're turning Italy's judicial real estate auction market — historically
buried in scanned PDF court documents — into structured, queryable data.

Before AECS4U I spent 25+ years in aerospace engineering (Airbus, Atkins,
Ricardo, Assystem) on aircraft structural assembly and certification, while
working in Python, ML and (more recently) Rust on the side. The PropTech
pivot started when I noticed Italian judicial auctions have every hallmark
of an inefficient market: the data exists but is locked in unstructured
formats, valuation is artisanal, and capital allocation is dominated by
local insiders. Worth fixing.

---

## 🛠 What I'm building right now

### AECS4U data platform

A document-understanding pipeline for Italian judicial real estate
auctions. End-to-end:

- **OCR & extraction** — olmOCR2 → custom chunker → Claude Haiku labeler →
  ShareGPT JSONL training data
- **Fine-tuning** — QLoRA on Qwen 2.5 via Axolotl
- **Inference** — vLLM with `guided_json` for schema-constrained output
- **API layer** — FastAPI + SQLModel + PostgreSQL on DigitalOcean

Document types in scope: *perizie tecniche*, *ordinanze* and *avvisi di
vendita*, *contratti di locazione*, *visure storiche / attuali*, and
*ispezioni ipotecarie*.

### PCMI — Property Comparables & Market Intelligence

A multi-source valuation surface for distressed property assets. Pulls from
Idealista, Borsino Pro, Openapi SpA, OMI and CASAFARI into a
confidence-weighted comparables view. Goal: replace artisanal valuation
with something an investor can underwrite from.

### RAO — Resume AutoResearch Optimiser

A three-component ATS scoring system (CV / cover letter / job-description
match) with a 17-check ATS engine and a multi-profile system that swaps
between career tracks — CTO, senior engineer, PropTech / data, aerospace /
systems, EU institutional — via a `profiles.json` selector.

---

## 📚 Background

**Aerospace** — 25+ years across Airbus, Atkins, Ricardo and Assystem.
Most recently Technical Team Leader on the A350 nose and centre fuselage
structural assembly team. Chartered Engineer (CEng).

**Software** — Python since the late 2000s, Rust since 2022, TypeScript
when something has to render in a browser. FastAPI, SQLModel and PostgreSQL
are my default stack for shipping production services.

**ML / NLP** — Master's in Non-Performing Loans Management (2025). Active
in fine-tuning open-weight models for legal-domain document understanding
and structured extraction.

**GIS** — geospatial work threads through everything I do at AECS4U:
multi-floor cadastral mapping, competitive analysis of ~70 Italian auction
platforms, comparative studies of judicial-auction transparency across
25+ countries. I publish technical material in this space on LinkedIn.

---

🧰 Toolbox

---
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python Logo" width="50" height="50"/><br />
---

<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" alt="Node.js Logo" width="50" height="50"/><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript Logo" width="50" height="50"/><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="TypeScript Logo" width="50" height="50"/><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original-wordmark.svg" width="50" height="50"/><br />
---

<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original.svg" alt="GO Golang Logo" width="50" height="50"/><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rust/rust-plain.svg" width="50" height="50" /><img src="https://github.com/devicons/devicon/raw/master/icons/bash/bash-original.svg" alt="Bash Logo" width="50" height="50"/><br />
---

<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-plain-wordmark.svg" alt="MongoDB Logo" 
width="50" height="50"/> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-plain-wordmark.svg" alt="MySQL Logo" width="50" height="50"/> <img src="https://cdn.worldvectorlogo.com/logos/postgresql.svg" alt="PostgreSQL Logo" width="50" height="50"/><br />
---

<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/kubernetes/kubernetes-plain-wordmark.svg" alt="Kubernetes K8s Logo" width="50" height="50"/><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-plain-wordmark.svg" alt="Laravel Logo" width="50" height="50"/><br />
---

<img src="https://cdn.worldvectorlogo.com/logos/aws-2.svg" alt="AWS Logo" width="50" height="50"/><img src="https://github.com/devicons/devicon/raw/master/icons/heroku/heroku-original-wordmark.svg" alt="Heroku Logo" width="50" height="50"/>

You can reach me at 
[![](https://img.shields.io/badge/-Twitter-informational?style=for-the-badge&logo=twitter&logoColor=white&color=00aced)](https://twitter.com/emanuelecannizzaro) or at 
[![](https://img.shields.io/badge/-Linkedin-informational?style=for-the-badge&logo=linkedin&logoColor=white&color=2867B2)](https://linkedin.com/in/emanuelecannizzaro).


<!--
- 📸 Spare time photographer
- 🪐 Motobike passionate

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

[![GitHub Trophies](https://github-profile-trophy.vercel.app/?username=EmanueleCannizzaro)](https://github.com/ryo-ma/github-profile-trophy)
<img align="right" src="https://github-readme-stats.vercel.app/api?username=EmanueleCannizzaro&show_icons=true&theme=dracula" />
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=EmanueleCannizzaro&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

[![Stars](https://img.shields.io/github/stars/EmanueleCannizzaro?style=flat&color=black&logo=github&logoColor=white&label=stargazers)](https://github.com/EmanueleCannizzaro)
[![Followers](https://img.shields.io/github/followers/EmanueleCannizzaro?style=flat&color=purple&label=followers&logo=github)](https://github.com/EmanueleCannizzaro?tab=followers)
[![Sponsors](https://img.shields.io/github/sponsors/EmanueleCannizzaro?style=flat&color=blueviolet&logo=github&logoColor=white&label=sponsors)](https://github.com/sponsors/EmanueleCannizzaro)




**EmanueleCannizzaro/EmanueleCannizzaro** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:
-->
