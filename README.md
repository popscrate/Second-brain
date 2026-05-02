# Pops Crate · Second Brain

*The open-source AI-security architecture arm of Pops Holdings LLC. v0 is architecture documentation; sanitized component code lands in subsequent commits.*

---

## What this is

This is a folder you can read. That is the whole pitch.

The work in this repo is a personal-AI security architecture I have been building over the past six months — defense in depth across four layers, a discipline layer of cultural rules the system follows by convention, a coordinator-and-crew architecture that lets multiple AI faces work under one room without confusing the user, and a foundational-reality principle that names the actual privacy reality of cloud AI use before any feature pitch gets in the way.

It runs on my own desktop daily. It is not theoretical. The architecture description is here so other people can read it, fork it, argue with it, and build their own versions of the parts that make sense for their own work.

---

## Read these in order

If you want the *why* — the values, the beliefs about AI, the reason the work is shaped the way it is:

→ **[The Soul of the Brain](the-soul-of-the-brain.md)**

This is the values piece. ~2,400 words. Names what I believe about AI (the duck is the duck; AI does not remove the human), how I interact with the brain (loving-dad register, propose before execute, trust comes from inspection), what I believe about the user, and what I believe about the work. If only one of these three reads lands for you, this is the one I would want it to be.

If you want the *what* — the architecture, the principle, the substantive case:

→ **[The Foundational Reality of Personal AI](foundational-reality.md)**

This is the long read. ~2,400 words. Walks through the foundational-reality principle (anything submitted to a cloud model is submitted, period), the four-layer defense (hooks, audit, discipline, reactive lockdown), and the trust-comes-from-inspection-not-promise posture that ties them together.

If you want the *how* — the technical read-through, what each layer does, what each capability does, where the gaps are:

→ **[Security Architecture](security.md)**

This is the architecture map. ~3,600 words. Reads top to bottom or jumps to whichever layer matters to you. Threat model, four-layer description, capability list, principles, what is covered and what isn't, OWASP LLM Top 10 (2025) coverage matrix.

If you want to know who is building this and where it fits in their broader work, the rest of this README is for you.

---

## Status — what this repo is right now

v0 architecture documentation. The hooks, audit scripts, lockdown detector, and supporting code that the writeup and security map describe are all running in active daily use on my desktop, but the sanitization pass for public release is in flight. Code drops land in subsequent commits as each component clears the personal-paths-stripped review.

What that means for you:

- You can read the architecture today and see whether the shape lands
- You can verify the threat model is real and the gaps are named honestly
- You cannot yet `git clone` this and run it as a working stack — that comes in the next phase
- If you are working on adjacent things, there are patterns in the writeup and security map that are transferable as ideas even before the code lands

---

## Where this fits

Pops Crate is the open-source AI-security architecture arm of **Pops Holdings LLC** — a holding company organized around quality-over-everything. The other arms include Fond Memories (a mobile smoothie cart business pre-launch in Sahuarita AZ), Pops Productions (creative work — music, brand, content), and an eventual nonprofit breakfast restaurant called Pops Place. Same systems-thinking through all of it.

The internal version of this architecture — the brain I have been building for myself, with all my actual life in it — stays private. This repo is the public-facing version: the architecture description, the threat model, the principles, and (in subsequent commits) the sanitized code. The ideas are what's open. My family stays in the kitchen.

---

## Why "Pops Crate"

Two readings.

For most readers — *Pops's crate.* The wooden box of stuff he keeps under the bench, the box you go to when you need something specific and you know it'll be in there. *Pull from the crate. It's in the crate. I keep the good stuff in the crate.*

For technical readers — `crate` is the Rust package primitive. The double-meaning lands without forcing it.

The whole holding company is named after my father, a lifetime CPA who valued privacy with a kind of structural seriousness, and whose values seeded the foundational-reality principle this whole architecture is built around.

---

## Get in touch

- The values piece → [the-soul-of-the-brain.md](the-soul-of-the-brain.md)
- Architecture writeup → [foundational-reality.md](foundational-reality.md)
- Security architecture → [security.md](security.md)
- Email — popsholdingllc@gmail.com

If any of this resonates — the foundational-reality framing, the defense-in-depth architecture, the trust-via-inspection posture, or the broader thesis that AI does not have to remove the user from their own work — I would love to hear from you. This work is better with collaborators.

---

## License

MIT. The intent is for this work to be usable, forkable, audit-able, and improvable by anyone who finds it useful. The dignity is in the architecture being verifiable, not in it being proprietary.

---

*This is free because this matters. Trust comes from inspection, not promise.*

— Jacob Snell · Sahuarita, Arizona · 2026
