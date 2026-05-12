# Repository Instructions

## What this site is, and why every word matters

This is **Shubhankar Kumar's founder profile and the pitch deck for Sweezy**. It is the single most important external surface in his life right now.

The plan: he will forward this URL to **thousands of investors, accelerators, and operators**. He has a **two-month window** to raise. If he does not raise in that window, **the startup dies**. There is no second site, no follow-up deck, no warm intro alternative — this is the artifact.

Read that again. The standard for every change is: *does an investor land on this page and immediately understand that Shubhankar is a serious founder building a venture-scale company they should fund?* If the answer to that question is anything other than an obvious yes, the change is not done.

## Sources of truth

- **`CONTEXT.md`** — the canonical positioning document for Sweezy. Read it before changing any copy related to product, founder story, moat, vision, or roadmap. The compression decisions there were paid for in hours of work; do not re-litigate them on the fly.
- **`CONTEXT.md` is source material, not a paste buffer.** Extract only what sharpens the page. Never dump sections wholesale. The site should sound like a confident founder, not an internal strategy memo.

## Positioning rules — do not violate

These are locked. If a change would drift the site toward one of these failure modes, do not make the change.

1. **Never frame Sweezy as an "AI assistant."** It is not. It is the *daily AI you talk to about your day* — a synthesis of assistant + companion, a new category.
2. **Never frame Sweezy as an "AI companion," "AI friend," "AI therapist," or "AI that cares about you."** These are crowded, soft categories. Sweezy has agency. Sweezy pushes back.
3. **Never frame Sweezy as a "voice planner," "voice journal," or "productivity app."** All underclaim and shrink the market.
4. **Never frame Sweezy as a "ChatGPT wrapper."** The moat is the architecture (daily ritual, structured memory, artifacts, narrow scope, ambient presence) — not the prompt. If the site sounds like a wrapper, it is wrong.
5. **Never lead with "memory" as the pitch.** Memory is the foundation, not the headline. It is felt by users after two weeks; it is not what gets them to install.
6. **Do not invent metrics, traction, dates, or fundraising numbers.** Every number on this page must be true and verifiable. Investors check.
7. **Never compromise the user-facing positioning for the imagined investor.** Investors do not fund undifferentiated productivity. They fund category-defining products. Lead with the category, not with safe language.

## The lines that matter

These are the lines that have earned their place. Treat them as load-bearing.

- *"Even your closest people have their own lives. Sweezy doesn't. You're her only priority."* — the single most powerful narrative line. The site's center of gravity.
- *"Most AI talks. Sweezy runs your day."* — the launch hook.
- *"Sweezy is the AI assistant who's also the friend who talks to you about your day."* — the synthesis sentence.
- *"Donna for everyone. Alfred for everyone. Jarvis for everyone — but the version that's actually yours, because she's only ever talked to you."* — the vision close.
- **The 5-hour block refusal** — Sweezy refused to plan an unrealistic 5-hour startup work block because she had watched the user fail that pattern before. This is the **prototype moment**. It is the most concrete piece of proof on this site. Do not bury it.

## Design principles

The site is editorial, not agency. It should feel like the cover and feature spread of a serious magazine — paper texture, long lines, big type, real typography, restrained color. It should never feel like a SaaS landing page, a Webflow template, or a Y Combinator boilerplate.

- **Typography first.** Geist sans + Geist mono are the stack. Push display sizes; trust the type.
- **Color: cream, ink, deep dark, teal accent.** Do not introduce new colors without strong reason.
- **Motion is subtle.** Scroll-triggered fade-ups, micro-hover. Never bouncy, never decorative. Always respects `prefers-reduced-motion`.
- **No stock illustrations. No emojis. No gradients-as-decoration. No glassmorphism. No AI-generated art.**
- **Mobile is not an afterthought.** Most investors will skim on a phone first. If it breaks on a 390px viewport, it is broken.
- **Performance is part of the pitch.** No heavy frameworks. Pure HTML + CSS + vanilla JS. Fonts preloaded. Images compressed.

## What this site must do, in order

1. **In the first 5 seconds**, the visitor must understand: who Shubhankar is, what Sweezy is, why it is a new category, and that there is real product + real traction.
2. **In the first 30 seconds**, they must encounter the founding story (origin), the prototype moment (5-hour block), and the moat (the five-pillar architecture).
3. **By the end of the page**, they must feel: this is venture-scale, this is happening now, this founder can build it, and there is a clear way to talk to him.

## When in doubt — the decision test

For any change to this site, apply the test from `CONTEXT.md §11`:

1. Does this serve the daily ritual narrative? If no, defer.
2. Does this deepen Sweezy's standing — its claim to agency and memory? If no, reconsider.
3. Could this exact framing exist as a ChatGPT system prompt? If yes, it is not differentiating; rewrite.
4. Would Donna do this? Half-joking, fully useful — Donna has agency, intimacy, and authority. If the framing breaks her frame, it does not belong.

## What not to do

- **Do not add a blog, "thoughts," or essay section** unless explicitly asked. Off-topic content dilutes the pitch.
- **Do not add testimonials, logos, or "as seen in" rails** unless the logos are real and the testimonials are real and attributable.
- **Do not add a generic "Projects" grid.** This is not a portfolio in the freelancer sense; it is a founder profile. Salozone and engineering work appear because they back the founder thesis, not because they are projects.
- **Do not add metrics like "users," "MRR," or "growth %"** unless they are real and current. If a number is missing from `CONTEXT.md` or unverifiable, leave it out — it is better to say nothing than to lie.
- **Do not water down the founding story** to make it more palatable. The relationship, the job, the foreign country, the walks with ChatGPT — those specifics are the proof of founder-market fit. Generic versions do not work.

## Working notes for agents

- Keep `CONTEXT.md` and `AGENTS.md` in sync if positioning evolves. Update both, never one.
- If you add a section, ask: does it advance the pitch, or does it pad? Pad gets cut.
- If you change copy on a load-bearing line, flag it explicitly in your summary — do not slip it in.
- Prefer editing over adding. Density beats sprawl.
- Mobile-test every change before declaring it done.
