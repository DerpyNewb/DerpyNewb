## Yohann Mar Gayao

Computer Science graduate (AI specialisation), Baguio City, Philippines. Open to remote work.

I build software around language models and then check whether the output holds up — which usually
matters more than the model choice. Most of what is here is a full thing that works end to end rather
than a snippet: the data layer, the model call, the validation, and the part that decides what to do
when the answer is wrong.

From 04/2025 to 08/2026 I was Project Assistant VI on **Project CrimeXPerience**, a two-year DOST-funded
XR crime scene simulation for Philippine criminology and forensics training, where I built the
Gemini-powered NPC witness interviews and the Firebase services behind them, automated the project's log
processing, survey analysis and document generation in Python, and trained the instructors who ran it.

### Projects

**[SQL-Agent-Demo](https://github.com/DerpyNewb/SQL-Agent-Demo)** — Ask a plain-English question, Claude
writes the SQL, it runs against a Cloudflare D1 dataset, and you get an answer built from the rows that
came back. A bounded tool-calling loop with SELECT-only validation on the model's output, because the
interesting part of an agent is what you do when the model is wrong.
`Cloudflare Workers` · `D1` · `Anthropic SDK`

**[automation-portfolio](https://github.com/DerpyNewb/automation-portfolio)** — Paste a job posting URL:
fetch it, strip it, a model extracts structured fields, a validation layer checks them, and the result
appends to a Google Sheet. Every node routes its failures to a separate tab rather than dropping them.
The validation suite is not tied to one provider — it stayed green through an Anthropic-to-Gemini swap,
unmodified.
`n8n` · `Gemini` · `Google Workspace`

**[Grand-Trade-Exchange](https://github.com/DerpyNewb/Grand-Trade-Exchange)** — A commodities market and
stock exchange for Total War: WARHAMMER III: 17 live-priced goods, faction shares, standing orders and a
custom UI panel, all generated and self-tested from a single Python source. 24,751 lines of generator
code emitting the database tables, the campaign Lua and the interface layouts.
`Python` · `Lua` · `relational game databases`

**[Chaos-Dwarf-House-Ancillaries](https://github.com/DerpyNewb/Chaos-Dwarf-House-Ancillaries)** — 430
pieces of equipment and four campaign routes that earn them, including 30 battle abilities written for
the mod. Same approach: one Python source owns the items, and the 31 database tables, 1,350 localisation
strings and the UI all fall out of it. A `--check` mode regenerates every committed file, so the repo
cannot drift from its generator without `git diff` saying so.
`Python` · `Lua` · `code generation`

Both mods come out of a modding practice I have kept up since 2020, which is where I learned to work
against large relational databases and an undocumented API — and to build the tests myself, since the
engine reports runtime script errors with no message at all.

### Research

**Photogrammetry and Neural Radiance Fields for Cultural Preservation** — lead researcher. Built the
evaluation pipeline, benchmarked NeRF variants (Splatfacto, Instant-NGP, Nerfacto) against traditional
photogrammetry under controlled conditions, and scored outputs on STD, RMSE, and MAE to report the
cost-versus-fidelity trade-off rather than declaring a single winner. Presented at the Philippine
Computing Science Congress (PCSC) and the AUDRN Conference.

### Toolkit

Python · Java · SQL · Lua · C#
Gemini and Anthropic APIs · prompt design and iteration · Claude Code, used daily
Unity · Godot · Firebase · Cloudflare Workers

### Contact

yohanng500@gmail.com
