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

<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="TypeScript" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" alt="Node.js" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" alt="React" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original.svg" alt="Go" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/rust/rust-plain.svg" alt="Rust" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bash/bash-original.svg" alt="Bash" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original.svg" alt="MySQL" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg" alt="MongoDB" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" alt="Docker" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/kubernetes/kubernetes-plain.svg" alt="Kubernetes" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original.svg" alt="AWS" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/heroku/heroku-original.svg" alt="Heroku" width="40" height="40"/>
</p>

You can reach me at 
[![](https://img.shields.io/badge/-Twitter-informational?style=for-the-badge&logo=twitter&logoColor=white&color=00aced)](https://twitter.com/emanuelecannizzaro) or at 
[![](https://img.shields.io/badge/-Linkedin-informational?style=for-the-badge&logo=linkedin&logoColor=white&color=2867B2)](https://linkedin.com/in/emanuelecannizzaro).

<p align="center">
  <a href="https://github.com/ryo-ma/github-profile-trophy">
    <img src="https://github-profile-trophy.vercel.app/?username=EmanueleCannizzaro&theme=dracula&row=1&column=7&margin-w=10" alt="GitHub Trophies" />
  </a>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=EmanueleCannizzaro&show_icons=true&theme=dracula&hide_border=true" alt="Stats" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=EmanueleCannizzaro&layout=compact&theme=dracula&hide_border=true" alt="Top Languages" height="165" />
</p>

<p align="center">
  <a href="https://github.com/EmanueleCannizzaro"><img src="https://img.shields.io/github/stars/EmanueleCannizzaro?style=flat&color=black&logo=github&logoColor=white&label=stargazers" alt="Stars" /></a>
  <a href="https://github.com/EmanueleCannizzaro?tab=followers"><img src="https://img.shields.io/github/followers/EmanueleCannizzaro?style=flat&color=purple&label=followers&logo=github" alt="Followers" /></a>
  <a href="https://github.com/sponsors/EmanueleCannizzaro"><img src="https://img.shields.io/github/sponsors/EmanueleCannizzaro?style=flat&color=blueviolet&logo=github&logoColor=white&label=sponsors" alt="Sponsors" /></a>
</p>
