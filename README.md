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

<p align="center">
  <a href="https://github.com/ryo-ma/github-profile-trophy">
    <img src="https://github-profile-trophy.vercel.app/?username=EmanueleCannizzaro&theme=dracula&row=1&column=7&margin-w=10" alt="GitHub Trophies" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/EmanueleCannizzaro"><img src="https://img.shields.io/github/stars/EmanueleCannizzaro?style=flat&color=black&logo=github&logoColor=white&label=stargazers" alt="Stars" /></a>
  <a href="https://github.com/EmanueleCannizzaro?tab=followers"><img src="https://img.shields.io/github/followers/EmanueleCannizzaro?style=flat&color=purple&label=followers&logo=github" alt="Followers" /></a>
  <a href="https://github.com/sponsors/EmanueleCannizzaro"><img src="https://img.shields.io/github/sponsors/EmanueleCannizzaro?style=flat&color=blueviolet&logo=github&logoColor=white&label=sponsors" alt="Sponsors" /></a>
</p>

---

You can reach me at 
[![](https://img.shields.io/badge/-Twitter-informational?style=for-the-badge&logo=twitter&logoColor=white&color=00aced)](https://twitter.com/emanuelecannizzaro) or at 
[![](https://img.shields.io/badge/-Linkedin-informational?style=for-the-badge&logo=linkedin&logoColor=white&color=2867B2)](https://linkedin.com/in/emanuelecannizzaro).
