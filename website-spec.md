# Website spec — one-page agency site

**Type:** single-page site, dark theme
**Primary goal:** one conversion — Book a call
**Traffic source:** cold/warm outreach (link is sent directly to a prospect, not found via search) — also being shared with the founder for internal review
**Base:** Islamabad, Pakistan — working nationwide

---

## Architecture

Nav plus thirteen sections, stacked, in this order:

| # | Section | id | Job it does |
|---|---------|----|----|
| 0 | Nav | — | Wordmark, anchor links, persistent Book a call button |
| 1 | Hero | `#hero` | States the offer directly: content production + marketing, for organizations and businesses |
| 2 | Proof bar | `#proof` | Sliding marquee of real client logos, immediately after the claim |
| 3 | Documentaries | `#work` | Long-form video work, 2-up video-player-style cards |
| 4 | Reels | `#reels` | Short-form vertical video work, 4-up caption-led cards |
| 5 | Ad Results | `#ad-results` | Paid campaign case studies — real numbers, clickable through to full write-ups |
| 6 | Testimonials | `#testimonials` | Sliding marquee of client quotes with initials avatars |
| 7 | Problems We Solve | `#problems` | Names the buyer's pain before pitching the fix |
| 8 | Services ("How We Help") | `#services` | Two services, described as outcomes, each with its own Book a call |
| 9 | Process | `#process` | Four steps — removes "what happens if I hire you" fear |
| 10 | Founder | `#team` | Single founder spotlight — photo, bio, award credential |
| 11 | FAQ | `#faq` | Common objections, answered before the call |
| 12 | Closing CTA | `#cta-wrap` | Same offer as the hero, repeated |
| 13 | Footer | — | Contact, socials, location, legal |

Nav anchors: Work · Services · Process · Team → all roads end at Book a call.
(Work, Reels and Ad Results share one nav anchor — `#work` — since they run back-to-back with no gap between them.)

**Note:** the original spec's "Results" section (stats + testimonials in one block) no longer exists as a standalone section. Its two real numbers (65 enrolled, 38 clients) now live inside **Ad Results**, and testimonials became their own dedicated, larger section (6 cards instead of 2).

---

## Services

Two services now, not three — content marketing and performance/paid ads were merged into one offer, since in practice they're sold and run together.

| # | Service | What it is | What the client gets |
|---|---------|-----------|----------------------|
| 01 | Content production | Documentaries, reels, ad creative | Footage built to be watched, not scrolled past |
| 02 | Content marketing & ads | Posting calendar + paid ads run on that same footage | Enquiries you can call — never just reach |

Each service card carries its own checklist of deliverables and its own **Book a call** button (not one shared CTA for both).

---

## Section copy

### 1 — Hero

**Eyebrow tag** (icon + text, pill above headline): Content Production · Marketing · Ads

**Headline**
> Content Production & Marketing
> for Organizations and *Businesses*.

*(accent word "Businesses" set in Instrument Serif italic, yellow)*

**Subhead**
> We shoot the content and run the campaigns — documentaries, reels and ads, produced and promoted by one team.

**Buttons:** Book a call (primary) · See our work (secondary)

No location note under the buttons (removed — was "Islamabad, Pakistan — working nationwide", cut per request). No hero visual/mockup — text-only hero, centered.

### 2 — Proof bar

Label: Trusted by
Logos (sliding marquee, infinite loop, pauses on hover): SCO · Alkhidmat Foundation Pakistan · Cisco · Kort · Foji's Ice Lounge · Alsager Delight · Wisdom School System

All seven logos are real client marks, background-removed and sized into identical chip boxes so mismatched source aspect ratios don't read as inconsistent.

### 3 — Documentaries

Heading: **Long-form, built to be *watched*.**
Lede: Field-shot documentaries and short films. Full case studies are being added as projects wrap — real client work only, nothing stock.

2-up grid (bigger cards than Reels/Ad Results, matching reference size).

- **Slot 1 — live embed:** "KORT SCO" (Vimeo `1217492082`)
- **Slot 2 — live embed:** "Bhimber SCO" (Vimeo `1217492020`)
- **Slot 3 & 4 — placeholder:** fake video-player card (play button, "Sound off" chip, caption, scrubber, timestamp) standing in until more footage is uploaded

### 4 — Reels

Heading: **Short-form, built for *the scroll*.**
Lede: Vertical, caption-led, made for the feed.

4-up grid, 9:16 vertical cards. Each placeholder shows a bold caption/hook word overlaid mid-frame plus a small corner play icon and a bottom caption chip ("Reel 01"–"Reel 04"). All four still placeholders — no reel footage uploaded yet.

### 5 — Ad Results

Heading: **Campaigns, *measured*.**
Lede: Real client work. Numbers are measured, not estimated — click through for the full case study.

4-card grid, each card a link (`[CASE STUDY LINK]` placeholder href) wrapping a video-player-style card tagged "Case Study", plus a big stat number and result line.

| Card | Stat | Detail |
|------|------|--------|
| 1 (real) | **65** | students enrolled in 30 days — paid campaign built and run end to end (academic institute) |
| 2 (real) | **38** | clients acquired in 30 days — content and paid ads run together (digital marketing academy) |
| 3 (placeholder) | `[Number]` | `[Result description — details to follow]` |
| 4 (placeholder) | `[Number]` | `[Result description — details to follow]` |

### 6 — Testimonials

Heading: **What it's like to *work with us*.**
Lede: "Sample layout — real client quotes go here before this goes live."

Sliding marquee (same technique as the logo bar — duplicated track, `translateX(-50%)`, pauses on hover), 6 unique cards, alternating tilt (`-2deg`/`+2deg`, straightens on hover). Each card: quote mark, quote text, initials avatar (colored yellow/lilac/navy, cycling) + name + role/organisation.

**All 6 are fictional placeholder people/companies** — deliberately not the real logo clients (SCO, Al‑Khidmat, etc.), since fabricating quotes and attaching them to a real organisation would misattribute words to an actual company. Swap for real testimonials before this section goes live:

| Initials | Name | Role, Organisation |
|---|------|---------------------|
| HM | Hina Malik | Director of Programs, Horizon Relief Network |
| BA | Bilal Ahmed | Founder, Crestline Academy |
| ZF | Zoya Farooq | Head of Marketing, Meridian Health Group |
| OS | Omar Siddiqui | Co-Founder, Pinewood Retail Co. |
| AK | Areeba Khan | Admissions Lead, Silverline Institute |
| FQ | Farhan Qureshi | Operations Manager, Coastal Logistics Ltd. |

### 7 — Problems We Solve

Heading: **The reasons most content *doesn't work*.**
Lede: You've probably hit at least one of these before.

Four problem → fix cards (✕ problem statement, → fix statement):

1. Your content looks like everyone else's — same templates, same stock footage. → We shoot original documentary and reel content built around your actual story.
2. You post consistently, but it never turns into enquiries. → We pair the content with paid distribution built to convert, not just reach.
3. You've hired production and marketing separately, and the two don't talk to each other. → One team runs both, so the footage is built for the campaign it's going into.
4. You don't actually know if any of it is working. → We report against enrolments, clients and leads — never against impressions.

### 8 — Services ("How We Help")

Heading: **Two ways we *help you grow*.**
Lede: Most agencies either shoot or run ads. We do both, which is why the footage and the campaign are never fighting each other.

Card style: rotated sticker badge (yellow "Production" / lilac "Marketing & Ads"), heading, one-line description, checklist (colored checkmarks matching the badge color), **Book a call** button at the bottom of each card.

**01 Content production** — badge: Production
We shoot and cut documentaries, short films and ad creative — the raw material every campaign is built on.
- Documentary & short-form video shoots
- On-location field production
- Full edit, colour and sound
- Deliverables ready for every platform

**02 Content marketing & ads** — badge: Marketing & Ads
We turn one shoot into a posting calendar, then run paid ads using that same content — so every dollar of spend is backed by creative that's already proven to work.
- Weekly posting calendar & captions
- Paid ad creative using your footage
- Targeting, budget and bidding managed
- Monthly performance reporting

### 9 — Process

Heading: **Four steps, *no mystery*.**
Lede: You will know what happens in week one, and what lands at the end.

1. **Discovery** — A call to work out who you need to reach and what a win actually looks like in numbers.
2. **Story and strategy** — We agree the story, the channels and the target before a camera comes out of the bag.
3. **Produce** — We shoot, edit and build the campaign assets. You see cuts before anything goes live.
4. **Distribute and report** — Content goes out, ads go live, and you get numbers against the goal we set in step one.

### 10 — Founder

Heading: **Meet the *founder*.**
Lede: No account manager relaying messages — you're talking directly to the person running the work.

Two-column layout: bio content on the **left**, photo on the **right** (360px column, 4:5 portrait, real photo — `founder.jpg`).

- Rotated badge: "Award Winner"
- Name: **Horário Gofour**
- Title line: Founder, Skagen — **SEO Rising Talent Award Winner** (award text in yellow)
- Bio: four paragraphs — why Skagen exists (production/marketing gap), background and the award context, hands-on/no-account-manager positioning, location

The old 3-person team grid and the four "why us" boxes underneath it are both gone — replaced entirely by this single founder spotlight.

### 11 — FAQ

Heading: **Common *questions*.**
Lede: The things prospects usually ask before the call — answered before you have to.

Same four questions as before (unchanged): one service only? · pricing structure? · outside Islamabad? · what happens after booking?

### 12 — Closing CTA

Heading: **Tell us what you need people to do.**
**We'll tell you how we'd *get them to do it*.**

*(two lines — sentence break is a manual `<br>`, not just wrapping; font size tuned so each sentence fits on its own line)*

Lede: A 20-minute call. You'll leave with an honest read on whether we're the right team for it — including if the answer is no.
Buttons: Book a call · Email us instead

Rendered as a rounded, contained card (not full-bleed) — floating above the footer with margins on both sides, navy gradient background.

### 13 — Footer

Wordmark + one-line description · Contact (email, phone, booking link) · Navigate (Work, Services, Process, Team) · Socials (Instagram, LinkedIn, YouTube) · Copyright + Islamabad, PK

---

## Design tokens (dark theme)

| Token | Value | Use |
|-------|-------|-----|
| Yellow | `#F6DC00` | Primary accent — buttons, headline accent words, badges, checkmarks |
| Yellow deep | `#E2C700` | Quote marks, secondary accent |
| Lilac | `#B9B3FF` | Secondary accent — eyebrow labels, one service badge, one testimonial avatar color |
| Navy | `#6C63FF` | Tertiary accent — brightened from the original brand navy so it reads on a dark background |
| Navy deep | `#151246` | Dark panel gradients (Work, Closing CTA) |
| Black | `#0A0A0B` | Footer background |
| Ink | `#F4F2EC` | Body text (near-white — flipped from the original dark-on-light) |
| Muted | `#A8A5BE` | Secondary text |
| Bone | `#0A0912` | Page background (near-black — flipped from the original cream) |
| Bone dim | `#111022` | Alternate section background for subtle variation |
| Line | `rgba(255,255,255,.12)` | Borders, dividers |

**Type:** Inter (headings *and* body, mixed case — no more all-caps display font) · Instrument Serif italic (accent words inside headings, always yellow) · IBM Plex Mono (labels, metadata, eyebrows)

**Signature elements:**
- Two-tone headings: plain text + one italic serif accent phrase in yellow, on every section heading site-wide
- Sliding marquees (same technique, three places): trusted-by logos, testimonials
- Fake video-player chrome on placeholder video cards (play button, scrubber, timestamp, "Sound off" chip) so empty slots read as "waiting for footage," not broken
- Scroll-reveal animation (`IntersectionObserver` + `.reveal` class) — section blocks fade/slide up as they enter the viewport

---

## Fill-in checklist

Everything in square brackets in `index.html` still needs replacing:

- [x] Agency name — Skagen (done)
- [x] Founder name/photo/bio — Horário Gofour, `founder.jpg` (done)
- [x] Client logos — 7 real logos, background-removed (done)
- [x] Documentaries 1–2 — real Vimeo embeds (done)
- [ ] `[BOOKING LINK]` — nav, hero, both service cards, Ad Results case-study links, closing CTA, footer
- [ ] `[EMAIL]` — closing CTA, footer
- [ ] `[PHONE]` — footer
- [ ] `[INSTAGRAM]` / `[LINKEDIN]` / `[YOUTUBE]` — footer
- [ ] Documentaries 3–4 — replace placeholder cards with real Vimeo embeds
- [ ] Reels 1–4 — replace all four placeholder cards with real embeds
- [ ] Ad Results 3–4 — replace `[Number]` / `[Campaign name]` / `[Result description]` with real figures, and give all four cards real `[CASE STUDY LINK]` destinations
- [ ] **Testimonials — all 6 are fictional sample content and must be replaced with real client quotes before this section goes live** (see table above for what's currently placeholder)
- [ ] Open Graph image (`[OG IMAGE]`) and meta description still generic

---

## Notes on the copy and design decisions

**Full dark-mode retheme, not a tweak.** Body background, text color, and every hardcoded light-mode value (nav blur tint, button borders, icon borders, box-shadows) were flipped or rebuilt — this wasn't just swapping CSS variable values, several components needed bespoke fixes (e.g. a black border is invisible on a near-black card; a navy accent needed brightening to stay legible on a dark background).

**Video placeholders use fake player chrome, not blank boxes.** Since real footage arrives in batches, empty Documentary/Reel/Ad Result slots are styled to look like a video player waiting to load (play button, scrubber, timestamp) rather than a broken-looking empty rectangle — reads as "in progress," not "missing."

**Testimonials are clearly flagged as sample content in two places**: the section lede on the page itself, and this spec. Do not treat the six names/quotes as real client claims.

**Ad Results replaced the old standalone "Results" section.** Rather than a stats block sitting apart from the work, the two real numbers (65, 38) now live inside clickable case-study cards in the same visual language as Documentaries — stat and proof sit together.

**Founder over Team.** The site now presents one named, credentialed founder (with a real photo) rather than three placeholder team-member avatars — a stronger trust signal than three blank stripes with `[Name]` under them, and it matches how the site is actually being used right now (shared directly with the founder for review).

**Both numbers always carry the timeframe.** "65 students" is a claim; "65 students in 30 days" is a result. Never let them appear separated. (Unchanged from original spec — still holds.)

**No blog or insights section.** The site's traffic is outreach, not search. A blog is a maintenance cost with no return until that changes. (Unchanged.)

**No separate services page.** On a one-pager the services live as a section; splitting them out would only let visitors browse capabilities instead of recognising their own problem. (Unchanged.)
