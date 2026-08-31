## Dan Cockrell

I build specialized applications and developer tools, usually for workflows awkward enough that generic software does not fit them well.

The current work is deliberately small in number: finish the applications, keep the genuinely reusable tools, and build new interactive work only on the newer Godot and controlled-art pipeline.

### Applications

- [DR Companion](https://github.com/dancockrell/dr-companion) — a full desktop MUD client for DragonRealms built around Lich 5, with maps, scripting, sound, art, automation and a Tauri/React desktop interface.
- [Magi Reader](https://github.com/dancockrell/magi-reader-engine) — an illustrated, narrated reading engine with word-level highlighting, multilingual support and classroom workflows.
- [QuickGrade](https://github.com/dancockrell/quickgrade) — local-first paper-test grading from a camera or photographs, including written-answer workflows and spreadsheet/document export.

### Tools

The useful part of a project is often the tool that falls out of solving it.

- [Quartermaster](https://github.com/dancockrell/quartermaster) — capability-aware scheduler: a job runs only when the machine can prove its dependencies are available.
- [screen-capture-mcp](https://github.com/dancockrell/screen-capture-mcp) — gives an MCP client visual feedback from a Windows desktop or application window.
- [project-42-blockchain](https://github.com/dancockrell/project-42-blockchain) — peer-to-peer dual-signed event ledger for Godot; no token, mining or trusted server.
- [DR Genie settings](https://github.com/dancockrell/dr-genie-settings) — validated highlights and sparse sound alerts for DragonRealms in Genie.

The common theme is making unreliable or manual work inspectable and repeatable: explicit state, deterministic files, tests that fail loudly, and documentation that preserves why unusual decisions exist.

### Reading packs

Magi Reader keeps the engine separate from the books. The two maintained example packs are:

- [The Raven](https://github.com/dancockrell/the-raven-edgar-allan-poe-magi-reader)
- [The Gift of the Magi](https://github.com/dancockrell/the-gift-of-the-magi-o-henry-magi-reader)

### Interactive work

[World Aflame](https://github.com/dancockrell/world-aflame) is the card-game project worth continuing, with a [Godot port](https://github.com/dancockrell/world-aflame-godot) and a reusable peer-to-peer ledger split into its own library.

Future platform/action work is being built in Godot with a newer controlled character-art and animation pipeline. Older prototypes and their first-generation art pipelines are being removed rather than kept as historical portfolio material.

### Background

Twenty years teaching English in Thailand, South Korea, China and the United States. MEd in Learning Design and Technologies, MA in English. Earlier work included intelligence analysis in the US Army and technical writing for BASF in Korea.

That background shows up in the software: I care about whether a system explains itself, whether a user can recover when something goes wrong, and whether the documented workflow matches what the program actually does.
