## Dan Cockrell

Learning designer and developer. I build reading tools and narrative games
that run in a browser with no install, no account and no build step:
usually a single HTML file you can open by double-clicking.

That constraint isn't minimalism for its own sake. Anything a school can't
install, a teacher won't use.

Twenty years teaching English across Thailand, South Korea, China and the
US, an MEd in Learning Design and Technologies (4.0, With Distinction) and an
MA in English. Before that, intelligence analysis in the US Army and
technical communication for BASF's R&D group in Korea.

The through-line is narrower than the résumé suggests: pattern recognition,
and getting an idea across a language or culture gap intact. The tools here
are that work, automated.

### Reading tools

Narrated texts with word-level highlighting and comprehension passes, plus a
classroom layer that turns a reading into a graded assignment: QR check-in,
marking with or without a Google account.

- **The Raven**, Edgar Allan Poe
- **The Gift of the Magi**, O. Henry
- **QuickGrade**, automatic test grading

One engine underneath; each book is a content pack. Narration carries
word-level timings, so the highlight tracks the voice rather than
approximating it.

### Games

- **Ghost Front**: WW2 horror platformer. One file, ~12 MB, art embedded,
  no dependencies.
- **The Horrors of War**
- **World Aflame**: three-faction card game. Hotseat on one device, or
  peer-to-peer across two with no server in between.
- **The Long Night**: hand-built canvas RPG with a runtime-synthesized
  orchestra and no audio downloads.

Playable at **[dancockrell.itch.io](https://dancockrell.itch.io/)**.

### How it's made

Art and narration are generated locally on one workstation rather than
licensed per asset: ComfyUI driven from scripts instead of the node graph,
neural text-to-speech, and word-level timing extraction.

The interesting problem is rarely the model. It's the pipeline around it:
holding a character's face steady across two hundred frames, or getting
timings accurate enough that a highlight hasn't drifted by the third stanza.

### Working notes

Most repositories here carry a status document beside the code: what
changed, why, and what's still open. They're written for the version of me
who comes back in six months having forgotten everything.

*Teaching since 2006. Building since 2021. Based in Thailand.*
