## Yohann Mar Gayao

Computer Science graduate (AI specialization), Baguio City, Philippines. Open to remote work.

I build with LLMs rather than around them — shipping model-driven features into applications people
actually use, and measuring whether the output is any good instead of assuming it is.

Most recently Project Assistant VI on **Project CrimeXPerience**, a two-year DOST-funded XR crime scene
simulation for Philippine criminology and forensics training, where I built the Gemini-powered NPC
witness interviews and automated the project's log processing, survey analysis, and document generation
in Python.

### Projects

**[SQL-Agent-Demo](https://github.com/DerpyNewb/SQL-Agent-Demo)** — Ask a plain-English question, Claude
writes the SQL, it runs against a Cloudflare D1 dataset, and you get a grounded answer. A bounded
tool-calling loop with SELECT-only validation on the model's output, because the interesting part of an
agent is what you do when the model is wrong.
`Cloudflare Workers` · `D1` · `Anthropic SDK`

**[automation-portfolio](https://github.com/DerpyNewb/automation-portfolio)** — Paste a job posting URL:
fetch it, strip it, an LLM extracts structured fields, a validation layer checks them, and the result
appends to a Google Sheet. Every node routes its failures to a separate tab rather than dropping them.
The validation suite is model-agnostic — it stayed green through an Anthropic-to-Gemini swap, unmodified.
`n8n` · `Gemini` · `Google Workspace`

**[Grand-Trade-Exchange](https://github.com/DerpyNewb/Grand-Trade-Exchange)** — A commodities market and
stock exchange for Total War: WARHAMMER III: 17 live-priced goods, faction shares, and a custom UI panel,
all generated and self-tested from a single Python source. From a modding practice I've kept up since 2020,
which is where I learned to work against large relational databases and an undocumented API.
`Python` · `Lua` · `relational game databases`

### Research

**Photogrammetry and Neural Radiance Fields for Cultural Preservation** — lead researcher. Built the
evaluation pipeline, benchmarked NeRF variants (Splatfacto, Instant-NGP, Nerfacto) against traditional
photogrammetry under controlled conditions, and scored outputs on STD, RMSE, and MAE to report the
cost-versus-fidelity trade-off rather than declaring a single winner. Presented at the Philippine
Computing Science Congress (PCSC) and the AUDRN Conference.

### Toolkit

Python · Java · SQL · Lua · C#
Gemini and Anthropic APIs · prompt design and iteration · Claude Code as a daily driver
Unity · Godot · Firebase · Cloudflare Workers

### Contact

yohanng500@gmail.com
