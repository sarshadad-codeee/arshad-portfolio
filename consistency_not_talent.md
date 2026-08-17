# Consistency, Not Talent / Frame, Not Upstage

## Part 1: What makes the site feel intentional (already in place)

- **Two fonts, fixed roles**: JetBrains Mono for headings, Inter for body — never mixed or swapped, so nothing feels random.
- **A small, fixed palette**: Ink (#14171C), Paper (#FAFAF9), Signal teal (#1B7A6B), Accent (#33415C). Four colors, used consistently — the teal never appears for random decoration, only for the logo, CTAs, and links.
- **One logo, reused everywhere**: the "AA" monogram with the terminal cursor "_" detail, same teal square, same position, across every page and now the favicon too.

None of this required design talent — it required deciding once and repeating it, which is the actual point of this exercise.

## Part 2: The design frames the work, it never upstages it

My real judgment call here: the site deliberately stays quiet. No gradients, no animation, no decorative flourishes competing with the actual content. The teal only shows up where it's functional — a button, a link, the logo — never as background decoration behind text. When I added the CV Checker embed and the Training Prep Agent's decision-flow diagram, I kept both visually plain (a bordered box, a monospace code block) specifically so the *content* is what a visitor's eye lands on, not the styling around it. The site's job is to prove the work is real — flashy design would actually undercut that claim, not support it.

## Part 3: AI image generation — judged, not just generated

Brief: generate several options, reject most, keep one, and know when a real screenshot beats a generated image entirely.

I generated 4 real candidate designs for a redesigned social-share (OG) image — a genuine gap I'd already flagged earlier ("Break Your Own Site") since my current OG image (`hero.png`, 1360×500) isn't sized correctly for social cards (ideal is ~1200×630).

**Candidate A (dark, minimal)** — On-brand colors, clean type. Rejected: badly unbalanced — all content crammed top-left, the entire bottom half is dead space. Looks unfinished, not minimal.

**Candidate B (paper background, bold)** — Same balance problem as A, just inverted colors. Rejected for the same reason.

**Candidate C (split panel, teal block right)** — **Selected.** Actually fills the 1200×630 frame properly instead of leaving half of it empty. The teal block anchors the monogram, the text sits clearly on the paper side, and it reads correctly even as a small thumbnail in a social feed, which is the real test for an OG image.

**Candidate D (busy grid background, "Click Here!" button)** — Deliberately built this one to be bad, to practice real rejection. Rejected for two genuine reasons: the tagline text overflows the canvas and gets cut off mid-word ("Trainin—"), and "Click Here!" is exactly the generic, hype-y language my whole site's identity is built to avoid ("no demo-only shortcuts").

**On real screenshots vs. generated images**: I didn't generate anything to replace the CV Checker case study screenshots (`cv_home.png`, `cv_results-1.jpg`) — those are real interface captures, and no generated image could serve as credible proof the tool actually works. Generated visuals are fine for brand/identity assets (like this OG image); they're the wrong tool entirely for proof-of-work evidence.
