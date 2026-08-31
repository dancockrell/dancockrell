## Dan Cockrell

I build specialized applications and developer tools, usually around workflows that are awkward enough that generic software does not fit them well.

My current work falls into three overlapping areas: full applications, tools for building and testing them, and a small number of game/interactive projects where the underlying systems are worth developing further.

### Applications

- [DR Companion](https://github.com/dancockrell/dr-companion) — a full desktop MUD client for DragonRealms built around Lich 5, with maps, scripting, sound, art, client automation and a Tauri/React desktop interface.
- [Magi Reader](https://github.com/dancockrell/magi-reader-engine) — an illustrated, narrated reading engine with word-level highlighting, multilingual support and classroom workflows.
- [QuickGrade](https://github.com/dancockrell/quickgrade) — local-first paper-test grading from a camera or photographs, including written-answer workflows and spreadsheet/document export.

### Tools

I keep the tools as first-class repositories when the tool is useful beyond the project that caused it to exist.

- [Quartermaster](https://github.com/dancockrell/quartermaster) — capability-aware scheduler: a job runs only when the machine can prove its dependencies are available.
- [screen-capture-mcp](https://github.com/dancockrell/screen-capture-mcp) — gives an MCP client visual feedback from a Windows desktop or application window.
- [gf-forge](https://github.com/dancockrell/gf-forge) — scripted production layer over ComfyUI for repeatable image, video and audio jobs.
- [gf-pipeline](https://github.com/dancockrell/gf-pipeline) — turns annotated art plates into indexed sprite data with shared palette, baseline and deterministic reduction.
- [project-42-blockchain](https://github.com/dancockrell/project-42-blockchain) — small peer-to-peer dual-signed event ledger for Godot; no token, mining or server.

The common theme is making an unreliable or manual workflow inspectable and repeatable: explicit state, deterministic files, tests that can fail loudly, and tools that preserve the reason behind unusual engineering decisions.

### Reading packs

Magi Reader keeps the engine separate from the books. Public-domain titles live in their own repositories so content, art and narration can evolve without hard-coding a title into the application.

- [The Raven](https://github.com/dancockrell/the-raven-edgar-allan-poe-magi-reader)
- [The Gift of the Magi](https://github.com/dancockrell/the-gift-of-the-magi-o-henry-magi-reader)

Other reader repositories are production experiments or incomplete packs rather than separate applications.

### Interactive work

[World Aflame](https://github.com/dancockrell/world-aflame) is the current card-game experiment. The reusable ledger work that came out of its networking problem lives separately in [project-42-blockchain](https://github.com/dancockrell/project-42-blockchain).

For future platform/action work I am using Godot and a newer controlled character-art pipeline rather than treating older game prototypes as permanent products.

### Background

Twenty years teaching English in Thailand, South Korea, China and the United States. MEd in Learning Design and Technologies, MA in English. Earlier work included intelligence analysis in the US Army and technical writing for BASF in Korea.

That background shows up in the software: I care about whether a system explains itself, whether a user can recover when something goes wrong, and whether the documented workflow matches what the program actually does.
