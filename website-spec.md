# Website spec — one-page agency site

**Type:** single-page site
**Primary goal:** one conversion — Book a call
**Traffic source:** cold/warm outreach (link is sent directly to a prospect, not found via search)
**Base:** Islamabad, Pakistan — working nationwide

---

## Architecture

Nine sections, stacked, in this order:

| # | Section | Job it does |
|---|---------|-------------|
| 0 | Nav | Wordmark, anchor links, persistent Book a call button |
| 1 | Hero | Who you help and what result they get, in one line |
| 2 | Proof bar | Client names, immediately after the claim |
| 3 | Featured work | Three projects with measured outcomes |
| 4 | Services | Three services, described as outcomes |
| 5 | Process | Four steps — removes "what happens if I hire you" fear |
| 6 | Results | The 65 and the 38, plus testimonials |
| 7 | Team / why us | Faces and reasons |
| 8 | Closing CTA | Same offer as the hero, repeated |
| 9 | Footer | Contact, socials, location, legal |

Nav anchors: Work · Services · Process · Results · Team → all roads end at Book a call.

---

## Services

| # | Service | What it is | What the client gets |
|---|---------|-----------|----------------------|
| 01 | Content production | Documentaries, reels, video content | Stories people watch to the end |
| 02 | Content marketing | Social media strategy and distribution | Consistent presence, one shoot marketed for months |
| 03 | Performance marketing | Paid ads | Enquiries you can call — leads, not reach |

---

## Section copy

### 1 — Hero

**Headline**
> Films that move people.
> Campaigns that fill seats.

**Subhead**
> We produce documentaries and social video for nonprofits, and run content and ad campaigns that bring institutes real enrolments — not impressions.

**Buttons:** Book a call (primary) · See the work (secondary)
**Note under buttons:** Islamabad, Pakistan — working nationwide.

**Slate card (right side)**
- Selected clients: SCO / Al-Khidmat Foundation / Kashmir Orphan Relief Trust
- Capabilities: Production · Content · Performance
- Base: Islamabad, PK
- Status: Taking new projects

### 2 — Proof bar

Label: Trusted by
Names: SCO · Al-Khidmat Foundation · Kashmir Orphan Relief Trust · [Academic institute] · [Digital marketing academy]

### 3 — Featured work

Heading: **Three projects, three outcomes.**
Lede: Every project below is real client work. Numbers are measured, not estimated.

**Card 1 — Documentary work for nonprofits**
Field-shot documentary and short-form video for SCO, Al-Khidmat Foundation and Kashmir Orphan Relief Trust — built to be watched to the end, not scrolled past.
Result line: 3 national organisations served
Tags: Documentary · Reels · Field production

**Card 2 — Enrolments for an academic institute**
We built and ran the paid campaign end to end: creative, targeting, landing flow and lead follow-up structure. The brief was enrolments, so that is what we reported on.
Result line: 65 students enrolled in 30 days
Tags: Performance · Creative · Lead gen

**Card 3 — Clients for a digital marketing academy**
Content marketing and paid ads run together — organic social built the trust, paid distribution put it in front of the right people, and the two compounded.
Result line: 38 clients acquired in 30 days
Tags: Content · Performance · Social

### 4 — Services

Heading: **Three services. One team, under one roof.**
Lede: Most agencies either shoot or run ads. We do both, which is why the footage and the campaign are never fighting each other.

**01 Content production** — Documentaries · Reels · Video
We shoot and cut documentaries, short films and social video. For nonprofits that means stories donors sit through and remember. For brands it means a library of footage you can market with for a year, not one video you post once.

**02 Content marketing** — Social strategy · Distribution
Footage is worthless sitting on a drive. We turn one shoot into a posting calendar across your social channels, then keep it running — so your audience hears from you every week instead of every quarter.

**03 Performance marketing** — Paid ads · Lead generation
We run the ads that bring you enquiries you can actually call. Creative, targeting, budget and follow-up structure — reported against enrolments, clients or leads, never against reach.

### 5 — Process

Heading: **Four steps, no mystery.**
Lede: You will know what happens in week one, and what lands at the end.

1. **Discovery** — A call to work out who you need to reach and what a win actually looks like in numbers.
2. **Story and strategy** — We agree the story, the channels and the target before a camera comes out of the bag.
3. **Produce** — We shoot, edit and build the campaign assets. You see cuts before anything goes live.
4. **Distribute and report** — Content goes out, ads go live, and you get numbers against the goal we set in step one.

### 6 — Results

Heading: **What 30 days looked like.**
Lede: Two campaigns, two clients, one month each. Both briefs were the same: bring people through the door.

| Figure | Client | Outcome | Detail |
|--------|--------|---------|--------|
| **65** | Academic institute | students enrolled | Paid campaign built and run by us, from creative through to lead handover. Achieved in 30 days. |
| **38** | Digital marketing academy | clients acquired | Content marketing and performance marketing run together over a single 30-day period. |

**Disclosure block (kept on the page deliberately):**
> Ad spend and internal campaign figures are withheld at our clients' request. We treat client data as confidential — yours will be handled the same way. Full breakdowns are shared on a call, with client permission.

Two testimonial slots below.

### 7 — Team / why us

Heading: **A small team you can actually reach.**
Lede: No account managers relaying messages. The people who shoot your film and run your ads are the people on the call.

Three team photos with name + role.

Why us:
- Production and media buying in one team, so the creative is built for the campaign it is going into.
- Trusted by national organisations including SCO, Al-Khidmat Foundation and Kashmir Orphan Relief Trust.
- We report against enrolments, clients and leads — the numbers your board or your bank account cares about.
- Based in Islamabad, shooting on location anywhere in Pakistan.

### 8 — Closing CTA

Heading: **Tell us what you need people to do. We'll tell you how we'd get them to do it.**
Lede: A 20-minute call. You'll leave with an honest read on whether we're the right team for it — including if the answer is no.
Buttons: Book a call · Email us instead

### 9 — Footer

Wordmark + one-line description · Contact (email, phone, booking link) · Socials (Instagram, LinkedIn, YouTube) · Copyright + Islamabad, PK

---

## Design tokens

| Token | Value | Use |
|-------|-------|-----|
| Pine | `#1E3A33` | Dark sections, slate card, stat blocks |
| Pine deep | `#152722` | Footer |
| Bone | `#E9E7DF` | Page background |
| Bone dim | `#DAD7CC` | Borders, dividers |
| Ink | `#14171A` | Body text |
| Marigold | `#E5A82E` | Buttons, stat figures, accents |

**Type:** Bricolage Grotesque (display) · Inter Tight (body) · IBM Plex Mono (labels, metadata, eyebrows)
**Signature element:** the clapperboard-style slate card in the hero, striped along the top edge.

---

## Fill-in checklist

Everything in square brackets in `index.html` needs replacing:

- [ ] Agency name — nav wordmark, footer wordmark, `<title>`, copyright line
- [ ] `[BOOKING LINK]` — hero button, closing CTA, footer (3 places)
- [ ] `[EMAIL]` — closing CTA, footer
- [ ] `[PHONE]` — footer
- [ ] `[INSTAGRAM]` / `[LINKEDIN]` / `[YOUTUBE]` — footer
- [ ] `[Academic institute]` and `[Digital marketing academy]` — proof bar (or drop if not permitted)
- [ ] Team names and roles ×3
- [ ] Two client testimonial quotes with name, role, organisation
- [ ] Three work stills replacing the striped placeholder blocks
- [ ] Three team photos replacing the striped avatars

Also worth adding: favicon, Open Graph image (the link gets pasted into DMs and WhatsApp — the preview card matters more than usual for an outreach-led site), and a meta description.

---

## Notes on the copy decisions

**Both numbers always carry the timeframe.** "65 students" is a claim; "65 students in 30 days" is a result. Never let them appear separated.

**The ad-spend restriction is framed as policy, not a gap.** A prospect reading "we withhold client figures on request" reads discretion. Left unexplained, the same absence reads as evasion.

**No blog or insights section.** The site's traffic is outreach, not search. A blog is a maintenance cost with no return until that changes.

**No separate services page.** On a one-pager the services live as a section; splitting them out would only let visitors browse capabilities instead of recognising their own problem.
