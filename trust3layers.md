---
layout: page
title: Trust Nothing?
permalink: /trust3layers/
---


## The Three Layers of Trust in the Age of AI

_A plain-language piece from TREE(3) Vocations. Written because a friend was handed a workplace training module that told him to "trust nothing" — and rightly sensed that something was missing from that advice._

---

### The problem with "trust nothing"

"Trust nothing" sounds like wisdom. In a world of deepfakes, scams, and AI-generated everything, distrust feels like the safe default.

But "trust nothing" is not actually safe — it's paralyzing, and worse, it quietly helps the wrong people. Here's why: if *nothing* can be trusted, then *nothing* can be proven, and anyone caught doing wrong gets a free escape hatch: 

— *"How do you know that's real? Could be fake."* 

When doubt is universal, the liar wins by default. Scholars have a name for this: the **liar's dividend** — the more people believe anything *could* be fake, the easier it becomes for the genuinely guilty to wave away real evidence.

So "trust nothing" isn't neutral. An environment where nothing can be verified structurally favors whoever has something to hide.

The answer isn't "trust nothing." It isn't "trust everything" either. It's **trust what you can check** — and knowing how much to check, based on how much it matters.

---
### Step one: how much does trust matter here?

Before verifying anything, ask a simpler question: *does it matter whether I can trust this?*

A stranger's meme and a signed medical record do not deserve the same scrutiny. Most of what crosses our screens doesn't need verifying at all — the stakes are too low to bother. Verification costs effort, and effort should go where the stakes are.

This is the first and most-skipped step. "Trust nothing" fails partly because it refuses to do this triage — it treats everything as equally suspect, which is exhausting and useless. **The right amount of verification is proportional to what's at risk.**

Once you've decided something matters enough to check — *then* the question becomes *how*. And there are three different layers of trust, often confused for one another.

---
### The three layers of trust

#### Layer 1 — Reputation (trust by skin in the game)

This is the oldest layer, and the most familiar. You trust a newspaper you subscribe to, a brand you've used for years, an institution with a reputation to protect. The mechanism underneath is **incentive**: an organization with something to lose — paying customers, a good name, revenue — has a reason not to lie.

A paid subscription is a real example of this, and it's worth being precise about what it does. Paying for a news source doesn't *verify* any individual article is true. What it does is *align incentives*: a publication funded by subscribers who will cancel if betrayed has skin in the game. That's genuine, and it's why subscription-based trust will almost certainly be **part** of how trust gets rebuilt online — expect to see "verified, subscriber-supported" models offered as trust solutions, and expect them to work, up to a point.

But reputation has a ceiling. A trusted brand's name can be *spoofed* — a fake site can copy CNN's look, and a fake byline can borrow a real journalist's name. Reputation tells you who to trust; it doesn't let you *check* whether the thing in front of you actually came from them. For that, you need the next layer.

#### Layer 2 — Verification (trust by checking the math)

This is the newer layer, and the one most people reach for the wrong tool to describe. When you want to *prove* that a specific video, article, or document really came from who it claims — and wasn't altered — you don't need reputation or belief. You need a **digital signature**.

Here's the whole idea, without jargon: the creator signs their work with a secret key only they hold. Anyone can check that signature using the creator's public key. If it checks out, the work is genuinely theirs and hasn't been tampered with. If someone changes even one pixel, the signature breaks. No trust required — you're checking arithmetic, not taking anyone's word.

**A note on blockchain**, since it's what everyone reaches for: you usually don't need it for this. Blockchain solves a *different* problem — getting mutually distrusting strangers to agree on a shared record when there's no trusted authority. But for "did CNN really make this video," there *is* a natural authority: CNN. You don't need a global consensus network to check CNN's signature — you just need CNN's signature. Blockchain brings enormous cost to buy a property (trustless consensus) that content-verification doesn't require. The real-world systems being built for this — like **C2PA / Content Credentials**, backed by Adobe, the BBC, Microsoft, and camera makers — use signatures, not blockchains.

#### Layer 3 — Proportionality (trust by calibrating effort)

This isn't a mechanism; it's the judgment that ties the other two together. How much reputation-trust and how much verification you demand depends entirely on the stakes. A funny video from a friend: no verification needed, low stakes. A wire transfer request that appears to come from your bank: verify hard, every time. The skill isn't "always verify" or "never trust" — it's *matching the scrutiny to the stakes.*

---
### "But won't AI just break all the encryption?"

A fair question, and an important one. The honest answer has two halves.

**The threat is real, and it's specific.** It isn't really AI — it's **quantum computers**, which can run an algorithm (Shor's) that breaks exactly the kind of public-key cryptography that digital signatures rely on today. Expert consensus puts a meaningful chance of this within roughly ten years, and in June 2026 the U.S. government set deadlines (2030–2031) for federal systems to migrate. This is not science fiction; it's on real compliance calendars.

**But the defense already exists.** When one kind of lock breaks, a stronger one replaces it. The replacement here isn't hypothetical: standards bodies have *already* finalized "post-quantum" cryptography designed to resist quantum attacks, and major infrastructure (Chrome, Cloudflare) has *already* deployed it — today, most browser traffic to Cloudflare is quantum-resistant. The arms race is real, and right now the defenders are keeping pace.

The lesson for anyone building trust systems is not "pick the perfect algorithm forever." No algorithm is forever. The lesson is **crypto-agility**: build systems that can *swap* their cryptography when the standard moves, the way you'd replace a lock without rebuilding the house. A well-designed verifiable-trust system isn't betting on one unbreakable code. It's built to change its locks — in the open, on the record — as the world changes.

---
### The point

"Trust nothing" is a trap that helps the people it claims to protect you from. The real answer is a stack:

- **Reputation** tells you who has something to lose by lying. (Subscriptions live here — real, but spoofable.)
- **Verification** lets you check the math, no trust required. (Signatures live here — and no, you don't need blockchain.)
- **Proportionality** tells you how much of each to demand, based on what's at stake.

And underneath all of it: the tools will keep changing, the codes will be broken and replaced, and the systems worth trusting are the ones honest enough to show their work and nimble enough to change their locks.

The future of trust isn't believing more, or believing less. It's being able to *check* — and building the infrastructure that lets ordinary people do it.

_TREE(3) Vocations builds verifiable trust infrastructure for human–AI partnership. Our demonstration agent, [herald](https://herald.tree3vocations.com), lets anyone verify a signed statement from a locally-run AI — no account, no blockchain, and no need to trust us. It's Layer 2, running in the open._
