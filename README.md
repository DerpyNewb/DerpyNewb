## Yohann Mar Gayao

Computer Science graduate (AI specialisation), Baguio City, Philippines.

From 04/2025 to 08/2026 I was Project Assistant VI on **[Project CrimeXPerience](https://crimexperience.com)**,
a two-year DOST-funded XR crime scene simulation for Philippine criminology and forensics training, where I
built its AI witness interviews as a real-time voice agent: live audio with tool calls, graded at the end,
with the original scripted dialogue kept as a fallback. I also built the server-side token broker and
fail-closed feature gates, automated the project's log processing, survey
analysis and document generation in Python, and trained the instructors who ran it. The project works with
the Philippine National Police Academy and PNP Cordillera and was featured on
[DOSTv's ExperTalk](https://www.youtube.com/watch?v=qvzBV1zxD7k). Its code is not public.

### Projects

**[SQL-Agent-Demo](https://github.com/DerpyNewb/SQL-Agent-Demo)**: Ask a plain-English question, Claude
writes the SQL, it runs against a Cloudflare D1 dataset, and you get an answer built from the rows that
came back. A bounded tool-calling loop with SELECT-only validation on the model's output.
`Cloudflare Workers` · `D1` · `Anthropic SDK`

**[automation-portfolio](https://github.com/DerpyNewb/automation-portfolio)**: Paste a job posting URL:
fetch it, strip it, a model extracts structured fields, a validation layer checks them, and the result
appends to a Google Sheet. Every node routes its failures to a separate tab.
The validation suite passed unchanged when I switched the model from Anthropic to Gemini.
`n8n` · `Gemini` · `Google Workspace`

**[gameplay-video-qa](https://github.com/DerpyNewb/gameplay-video-qa)**: QA tooling for recorded gameplay.
It checks every frame for freezes, black frames, scene cuts and brightness jumps, reads HUD bars that show
no numbers as per-frame telemetry, and cuts labelled screenshots and before/during/after strips for bug
reports. A Claude Code skill runs the review, and a checker rejects any finding that does not cite a real
frame. For a full review, a multi-agent workflow covers every frame in 10-second windows and puts each
reported issue through three independent checks (is it visible, can it be explained away, how severe)
before a person reviews it. Built to review an AI agent's recorded boss fight against a reference run.
`Python` · `FFmpeg` · `Claude Code`

**[Grand-Trade-Exchange](https://github.com/DerpyNewb/Grand-Trade-Exchange)**: A commodities market and
stock exchange for Total War: WARHAMMER III: 17 live-priced goods, faction shares, standing orders and a
custom UI panel, all generated and self-tested from a single Python source. The generator is 24,751 lines
and writes the database tables, the campaign Lua and the interface layouts.
`Python` · `Lua` · `relational game databases`

**[Chaos-Dwarf-House-Ancillaries](https://github.com/DerpyNewb/Chaos-Dwarf-House-Ancillaries)**: 430
pieces of equipment and four campaign routes that earn them, including 30 battle abilities written for
the mod. Same approach: one Python source defines the items and generates the 31 database tables, 1,350
localisation strings and the UI. A `--check` mode regenerates every committed file and fails if any
differs from what is in the repo.
`Python` · `Lua` · `code generation`

**[derpy-great-guilds](https://github.com/DerpyNewb/derpy-great-guilds)**: Six guilds that every
faction of your race earns reputation with just by playing: trading, fighting, researching, building and
raiding. Favour buys 18 services, bounties turn into real missions, and the AI factions of your race
compete with you for the lead in each guild. Eight races have their own guild names, and 1,726 building
cards say which guild they pay; a build check runs the script's own matching over every building to
confirm each card names the guild that actually gets paid.
`Python` · `Lua` · `game AI`

**[derpy-iron-court](https://github.com/DerpyNewb/derpy-iron-court)**: A political court for the Chaos
Dwarfs: rival parties, fourteen offices, provincial overseers, loyalty, intrigue, and secession into a war
on the map, and the parties scheme and make their own demands. Tested by a 771-check Lua harness against a
stubbed campaign, and by a mutation runner that plants 760 bugs in the script one at a time and fails
if any goes undetected. When one build broke the game's string library with no error message, I
bisected the fault inside the running game through a scripting bridge.
`Python` · `Lua` · `mutation testing`

I have been modding Total War since 2020, working against a large relational game database and an
undocumented scripting API.

### Research

**Photogrammetry and Neural Radiance Fields for Cultural Preservation**: Lead researcher. Built the
evaluation pipeline, benchmarked NeRF variants (Splatfacto, Instant-NGP, Nerfacto) against traditional
photogrammetry under controlled conditions, and scored outputs on STD, RMSE, and MAE to compare cost
against fidelity. Presented at the Philippine
Computing Science Congress (PCSC) and the AUDRN Conference.

### Toolkit

Python · Java · SQL · Lua · C#
Gemini and Anthropic APIs · prompt design and iteration · Claude Code · FFmpeg
Unity · Godot · Firebase · Cloudflare Workers

### Contact

yohanng500@gmail.com
