# Jonah → Framer (free plan) — Build Kit

You have two ways to get the landing page onto a `*.framer.website` URL. The exact hand-coded version is already live at **https://xatabik.github.io/jonah-landing/** — use it as the source or the reference.

---

## PATH A — Embed the existing design (≈5 minutes, pixel-identical)

Framer free supports custom-code **embeds**, so you can drop the whole live page into a Framer page as a full-screen frame.

1. Framer → **New Project** → choose a blank/desktop start.
2. Delete the default content on the page.
3. Insert → **Embed** (or the **Code/Embed** component).
4. Paste this:
   ```html
   <iframe src="https://xatabik.github.io/jonah-landing/"
           style="width:100vw;height:100vh;border:0;display:block"
           title="Jonah"></iframe>
   ```
5. Set the embed/frame to **fill** width and height (100%).
6. **Publish** → you get `yourname.framer.website`.

**Trade-offs:** fastest and keeps the exact design, but the page lives inside an iframe — so Framer's SEO/analytics see an empty shell, and you can't edit the content visually in Framer. Good as a quick live placeholder; not ideal long-term. *(If you later move off GitHub Pages, the iframe breaks — keep that repo published.)*

---

## PATH B — Rebuild it natively in Framer (≈30–60 min, fully editable, best SEO)

This is the "proper" Framer way — every block becomes editable, SEO-clean, and badge-removable later. Everything you need is below; just assemble it on the canvas.

### Fonts (Framer → Text → font picker → these are all free Google Fonts)
| Role | Font | Use for |
|---|---|---|
| **Display** | **Fraunces** (weight 500, slight italic for accents) | All headlines |
| **Body / UI** | **Archivo** (400–600) | Paragraphs, buttons, nav |
| **Labels / data** | **JetBrains Mono** (400–500) | Tiny uppercase tags, numbers, metrics |

### Color tokens (Framer → set as Color Styles)
| Name | Hex | Use |
|---|---|---|
| Ink (background) | `#0D0D0F` | Page background |
| Ink-2 | `#141417` | Cards / panels |
| Ink-3 | `#1C1C21` | Inner cards |
| Paper (text) | `#F3EFE6` | Primary text |
| Paper-dim | `#B6B1A6` | Secondary text |
| Steel | `#7C8590` | Muted labels |
| **Signal (accent)** | `#FF6A2C` | The constraint / buttons / highlights |
| Good | `#5FD08A` | Positive metrics |

> Aesthetic: dark "instrument panel," warm off-white text, one hot **signal-orange** accent reserved for *the constraint* and CTAs. Generous spacing. Don't spread the orange around — its power is scarcity.

### Section-by-section copy (paste-ready)

**NAV** — left: `● Jonah` (orange dot + Fraunces). Right: links `Method · Diagnosis · vs. Repricers` + orange button **Get early access**.

**HERO**
- Tag (mono, orange dot): `THEORY OF CONSTRAINTS · FOR AMAZON`
- H1 (Fraunces, "one constraint" in orange italic): **Every listing has *one constraint* holding back its profit.**
- Lede: **Jonah finds it, fixes it, and moves to the next.** Not a repricer that races you to the bottom — a diagnosis engine that tells you exactly which lever to pull, and which ones to leave alone.
- Email field + button **Join the waitlist →**
- Small note: *Early access for private-label Amazon brands. No spam, no card.*
- Right side: the **constraint funnel** (see "Hero visual" below).

**HERO VISUAL — the constraint funnel** (a dark card)
Four stacked bars, each narrower than the last (funnel shape). Highlight the **2nd** bar in signal-orange with a glow and a tiny `THE CONSTRAINT ◄` tag:
- `Impressions — 41,000` (100% width)
- `Clicks · CTR — 0.31%` ← **orange, the constraint** (84% width)
- `Conversions · CVR — 8.7% · healthy` (71% width)
- `Profit / unit — $3.20 net` (58% width)
- Footer line: **Verdict:** Clicks are the bottleneck — conversion is fine. You're priced 9% above market and two campaigns are losing money. **Do:** cut the wasteful spend, nudge price toward the median. **Don't:** add ad budget.

**PROBLEM** (tag `THE PROBLEM WITH EVERY OTHER TOOL`)
- H2: **Most tools pull the wrong lever — confidently.**
- Sub: Repricers race to the bottom. PPC tools throw budget at listings that don't convert. Nobody asks the one question that matters first: *what's actually holding this listing back?*
- Three cards:
  1. **Repricers compete on price** — Rule-based bots match or undercut rivals. Margins erode, the bot "wins" the Buy Box, your profit bleeds out.
  2. **PPC tools spend into leaks** — Pouring budget into a low-converting listing just buys expensive clicks that never become orders.
  3. **Black boxes you can't trust** — "The AI set your price." Why? Most tools can't say — so you can't hand over the one lever that runs your business.

**METHOD — the Five Focusing Steps** (tag `THE METHOD · GOLDRATT'S FIVE FOCUSING STEPS`)
- H2: **Diagnose before you prescribe.**
- Sub: Jonah runs the Theory of Constraints on every ASIN, around the clock. Find the bottleneck. Wring everything from it cheaply. Only then spend.
- Numbered list (big outlined Fraunces numerals):
  1. **Identify the constraint** — Walk the funnel (impressions, CTR, CVR, margin, inventory) and pinpoint the single stage throttling profit.
  2. **Exploit it — for free first** — Maximum profit from the constraint with zero spend: cut wasteful bids, fix the price, tune the offer.
  3. **Subordinate everything else** — Jonah's *don't-do* list stops you throwing ad budget at a conversion problem.
  4. **Elevate the constraint** — Once the free wins are banked, invest deliberately: scale ads, improve the listing, push rank.
  5. **Repeat — the constraint moves** — Break one bottleneck and another appears. Jonah re-diagnoses continuously.

**PROOF — a decision, not a dashboard** (tag `WHAT YOU ACTUALLY GET`)
- H2: **A decision, not a dashboard.**
- Sub: Every recommendation is ranked, reversible, and explained — with evidence and expected impact. Approve each move, or let Jonah handle it within your guardrails.
- A panel listing three rows:
  - `#1` **Cut campaign "Broad-Discovery."** 60% ACOS vs 21% breakeven — pure leak. **+$0.55/unit · reversible**
  - `#2` **Lower price $29.99 → $28.49.** Toward competitor median to lift CTR & CVR. **+8% weekly profit · within floor**
  - `✕` **Don't increase ad budget.** The bottleneck is CTR + ad waste, not traffic volume.

**VS** (tag `WHY JONAH`)
- H2: **Computed, not hallucinated.**
- Two columns. Legacy repricers (dimmed, `—` bullets): one input (competitor price) · races to the bottom · blind to ads/inventory/CVR · black-box changes · 60–90 days to learn. Jonah (orange, `+` bullets): diagnoses the real constraint · optimises margin × velocity = profit · coordinates price/ads/inventory · every move explained & reversible · category priors, useful day one.

**CTA**
- H2 (Fraunces, "Herbie" orange italic): **Find your *Herbie.*** *(In* The Goal*, Herbie is the slow scout — the bottleneck. Keep or cut this line.)*
- Sub: Early access is opening for private-label Amazon brands. Be first to put the Theory of Constraints to work on your catalog.
- Email field + **Request early access →**

**FOOTER**: `● Jonah` · *Theory of Constraints, run on your Amazon catalog 24/7.* · `© 2026 Jonah`

### Waitlist form in Framer
Framer's free plan has a built-in **Form** element — drop it in, set it to collect email, and connect it to your email or a Google Sheet in the form settings. No code needed.

---

## After either path
- **Custom domain** (e.g. `getjonah.com`): Framer free supports connecting one custom domain — buy the domain, add it in Framer → Site Settings → Domains.
- **Remove the "Made in Framer" badge:** requires the paid Mini/Basic plan (~a few $/mo).
- The GitHub Pages version stays live for free with **no badge** and clean SEO — a perfectly good option if you don't need Framer's visual editor.
