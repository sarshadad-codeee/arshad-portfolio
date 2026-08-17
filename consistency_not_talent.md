# Consistency, Not Talent — Full Deliverable
(The Through-Line + Decide Once + Kill Your Darlings)

## 1. One-line claim

**"From hackathon prototype to live tool — real input, real output, no demo-only shortcuts."**

## 2. Content map

All CTAs ladder to one action: emailing sarshadad@gmail.com.

| Page | Sections (in order) | Named CTA |
|---|---|---|
| **Home** (`index.html`) | Hero (one-line claim) → The Work: AI CV Checker → The Work: Training Prep Agent | "See the full rebuild →" (CV Checker), "See how it decides →" (Training Agent) |
| **Case Study: AI CV Checker** (`case-study.html`) | The Problem → What I Did → How It Works Now → Try It Live (embedded demo) → What Came of It → Get In Touch | "Open full app in new tab →", "View the code →", "Contact me →" |
| **Case Study: Training Prep Agent** (`case-study-training-agent.html`) | The Problem → What I Did → How It Works Now → Real Run: What Actually Happened (with decision-flow diagram) → What Came of It → Get In Touch | "Watch the demo video →", "Contact me →" |
| **About** (`about.html`) | Bio/background → proof statement context | "Contact me →" |
| **Contact** (`contact.html`) | Direct email CTA | "Email me →" |

**Still need to gather** (honest, open list):
- Usage analytics for CV Checker — no tracking on that separate app itself (portfolio site has GA4, the embedded app doesn't)
- A mentor testimonial — mentor was unreachable for an extended period; worth re-checking now
- A second, independent peer review specifically for the Training Prep Agent case study (currently only self-tested + one AI-assisted peer suggestion, disclosed honestly in that submission)

## 3. Identity kit (one page)

**Fonts:** JetBrains Mono (headings) + Inter (body) — two fonts, fixed roles, never mixed.

**Palette (hex codes):**
- Ink (near-black text): `#14171C`
- Paper (near-white background): `#FAFAF9`
- Signal (main accent, teal): `#1B7A6B`
- Accent (secondary text/links): `#33415C`

**Logo/favicon:** "AA" monogram, teal square background, white text, with a terminal cursor "_" detail — same mark used as both the nav logo and the browser favicon (16px, 32px, 180px sizes generated).

**Style note (2 lines):** Monospace headings and clean sans body keep it feeling built, not decorated. The palette stays quiet — teal only appears on functional elements (links, buttons, the logo) — so real work (screenshots, live demos) stays the most colorful thing on any page.

## 4. Final image set + rejection note

**Real captures used (not AI stand-ins):**
- `cv_home.png`, `cv_results-1.jpg` — real CV Checker interface screenshots, used in the case study
- `about.jpg` — real photo, used on the About page (compressed from 1MB → 22.8KB without visible quality loss)

**Generated images — judged, most rejected:**
Generated 4 candidate designs for a redesigned social-share (OG) image (a real gap: the previous OG image, `hero.png`, was 1360×500 — wrong aspect ratio for social cards, which need ~1200×630).

- **Candidate A (dark, minimal)** — Rejected: badly unbalanced, all content crammed top-left, bottom half empty. Looks unfinished.
- **Candidate B (paper, bold)** — Rejected: same balance problem as A.
- **Candidate C/final (split panel, teal block)** — **Selected and shipped live.** Fills the 1200×630 frame properly, reads correctly even as a small thumbnail.
- **Candidate D (busy grid, "Click Here!")** — Deliberately built as a bad example to practice real rejection. Rejected for two genuine reasons: tagline text overflows the canvas and gets cut off mid-word, and "Click Here!" is exactly the generic, hype-y language the whole site's identity is built to avoid.

The one consistent style across all generated candidates: same fonts, same 4-color palette, same monogram — so even the rejected options stayed on-brand, only their layout/balance/judgment differed.
