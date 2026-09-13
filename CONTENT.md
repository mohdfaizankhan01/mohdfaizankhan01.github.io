# Portfolio Content — Faizan Khan

Content-only source of truth for the portfolio: copy, links, and data.
No design, styling, or asset references.

---

## 1. Site metadata

| Field | Value |
|---|---|
| Page title | Faizan Khan — AI Builder & Mentor |
| Meta description | Faizan Khan — AI builder. I ship LLM agents, RAG and retrieval systems, and evaluation harnesses, grounded in the people they're for. MSc Computer Science, Université de Genève. |
| Author | Faizan Khan |
| Language | en |
| OG / Twitter title | Faizan Khan — AI Builder & Mentor |
| OG description | I turn messy human problems into AI tools that actually ship — LLM agents, RAG, evaluation harnesses. MSc CS, Université de Genève. |
| Twitter description | I turn messy human problems into AI tools that actually ship — LLM agents, RAG, evaluation harnesses. |

---

## 2. Navigation

**Brand:** Faizan Khan

| Label | Target |
|---|---|
| About | `#about` |
| Skills | `#skills` |
| Projects | `#projects` |
| Experience | `#experience` |
| Get in touch | `#contact` |

Stack (§8) and Writing (§9) are written below but not built, so they are not in
the menu: a nav link to a section that does not exist scrolls nowhere. Add the
row back at the same time the section ships.

---

## 3. Hero

- **Status:** Open to AI / ML roles
- **Headline:** I turn messy human problems into AI tools that actually ship.
- **Subline:** AI builder & mentor · Geneva
- **Buttons:**
  - View projects → `#projects`
  - Contact me → `#contact`

---

## 4. About

- **Eyebrow:** About
- **Heading:** A builder and mentor, not just a model-caller.

**Body copy:**

> I ship AI tools end-to-end and bring non-technical people along for the ride. Most of my work starts the same way: talking to the people the product is actually for, then letting those findings — not my assumptions — drive the design.

> I built an accessibility platform for disabled transit riders grounded in direct engagement with disability organisations, deployed LLM agents and evaluation systems, and led ML training for a 100+ member community.

> I'm driven by social-impact work, comfortable with ambiguity and resource constraints, and quick to scope what actually needs to exist versus what merely sounds impressive.

**Stats (4):**

| Number | Label |
|---|---|
| 5 | disability profiles scored, not one binary label |
| 9 | retrieval strategies fused into one ranking layer |
| 40% | faster data retrieval for non-technical staff |
| 4× | national / worldwide hackathon placements |

---

## 5. Skills — "Capabilities"

- **Eyebrow:** Capabilities
- **Heading:** What I bring to a team
- **Lead:** Five overlapping strengths — the AI build, the engineering underneath it, the research rigour around it, the design layer on top, and the human work that makes it land.

### Build with LLMs
LLM agents · prompt engineering · tool / output schemas · evaluation harnesses · RAG · automations & internal tools · Claude API · OpenAI · Groq · Ollama · LangChain

### Engineering
Python · SQL · FastAPI · SQLite · WebSocket · Git · ETL pipelines · reproducible workflows

### ML / NLP & research
dense & lexical retrieval · knowledge graphs · semantic embeddings · Transformers · ablation studies · deterministic benchmarking · CNNs / RNNs / GANs

### Working with people
stakeholder discovery · workshops for non-technical audiences · scoping & translating · documentation & handoff

### UI / UX Design
Figma · wireframing · prototyping · user research · interaction design · responsive design · accessibility-first · design systems · usability testing · information architecture

---

## 6. Projects — "Selected work"

- **Eyebrow:** Selected work
- **Heading:** Things I've built end-to-end
- **Lead:** Scoped, built, and shipped — backend to model to the humans on the other side.

### AIBility
- **Tag:** with disability orgs — **Year:** 2026
- **Role line:** Accessible mobility for disabled riders · UNIGE
- **Description:** A full platform for Geneva's TPG Flex transport: an LLM voice-booking agent for people who can't use the app, a crowdsourcing pipeline for community accessibility reports, and per-disability scoring for every stop — replacing a single misleading "accessible / not" label.
- **Stack:** FastAPI · SQLite · WebSocket · Groq LLaMA-3.3-70B · faster-whisper · OSRM · Epicollect5
- **Link:** View on GitHub → https://github.com/mohdfaizankhan01/AI.BILITY-tpgFlex

### RCnum Graph-RAG
- **Tag:** knowledge graph + RAG — **Year:** 2026
- **Role line:** Making archives usable by non-specialists · UNIGE
- **Description:** A retrieval-and-generation system that lets anyone query 13,640 16th-century Geneva archival records in plain French and get source-cited answers. Nine-strategy hybrid retrieval and a reference-free evaluation harness built from scratch — 0.88 recall, zero hard failures.
- **Stack:** GraphDB · SPARQL · ChromaDB · sentence-transformers · Mistral 7B · Groq · FastAPI
- **Link:** View on GitHub → https://github.com/mohdfaizankhan01/RCnum-Graph-RAG

### LIVPOL
- **Tag:** computational imaging — **Year:** 2026
- **Role line:** Privacy-preserving crowd estimation · UNIGE
- **Description:** An optical-encoding pipeline that separates crowd-density estimation from facial identity. Frequency-domain analysis shows density stays recoverable while identifying detail is suppressed by design — a privacy guarantee enforced at the optical layer, not bolted on after.
- **Stack:** NumPy · SciPy · Fourier analysis · signal / image processing · Matplotlib
- **Link:** None. Label: "Technical report & presentation"

### Factory Club Tees — Talk to a Database
- **Tag:** NL-to-SQL — **Year:** 2024
- **Role line:** Internal tool for non-technical retail staff
- **Description:** An LLM tool that lets retail staff query a database in plain English instead of SQL, cutting their data-retrieval time by 40%. A small thing that just needed to exist — and the kind of unglamorous build that quietly removes a daily bottleneck.
- **Stack:** LangChain · few-shot prompting · MySQL · Python
- **Link:** More on GitHub → https://github.com/mohdfaizankhan01

---

## 7. Experience & education

- **Eyebrow:** Path so far
- **Heading:** Experience & education

| When | Title | Organisation | Detail |
|---|---|---|---|
| Sep 2025 — Sep 2027 | MSc Computer Science | Université de Genève (UNIGE) | Applied NLP, retrieval-augmented generation, human-centred AI, and reproducible scientific computing. |
| Feb — Jun 2026 | AIBility & RCnum Graph-RAG | Academic projects · UNIGE | Two full-stack AI builds: an accessible-mobility platform with disability orgs, and a knowledge-grounded QA system over historical archives. |
| Sep 2025 — Present | IT Head | GESMA — Geneva English-Speaking Muslims Association · [gesma.ch](https://gesma.ch) | Handle the organisation's IT and web presence, making it easier for newcomers in Geneva to find and join. |
| 2026 — Present | Founding Engineer | DevArq · [devarq.tech](https://devarq.tech) | Built the data and automation layer: a scraping and enrichment pipeline over ~200 Swiss firms, scored for lead quality, feeding Gmail API outreach tooling. Client sites for architecture and design studios on top of it (live: [arcosdesign.net](https://arcosdesign.net)). |
| Jul 2023 — Jul 2024 | Data Science / ML Lead | Robogyan Society · [robogyan.tech](https://robogyan.tech) | Turned a 100+ member group into capable practitioners — ran hands-on workshops for mixed technical and non-technical members, and became the person people came to with ML questions. |
| Jul — Aug 2022 | Data Science Intern | TwoWaits Pvt Ltd | Built a content-based recommender over 5,000+ items using cosine similarity, >90% accuracy. |
| 2020 — 2024 | BTech Information Technology · GPA 8.2 / 10 | GGSIPU, Delhi | National Winner — Innovate@Sigfest · 4th Worldwide — Considition 2022 · Winner — Glitch Hackathon, SNU · 1st Runner-Up — NPCI ML Hackathon. |

---

## 8. Tech stack — "Tools I reach for"

- **Eyebrow:** Tech stack
- **Heading:** Tools I reach for

Python · SQL · FastAPI · SQLite · GraphDB · SPARQL · ChromaDB · sentence-transformers · LangChain · PyTorch · TensorFlow · HuggingFace · Groq · Ollama · Claude API · OpenAI · OSRM · WebSocket · Git · AWS · GCP · faster-whisper · Power BI · Tableau · scikit-learn · NumPy · SciPy · REST

---

## 9. Writing — "Notes from the build"

- **Eyebrow:** Writing
- **Heading:** Notes from the build
- **Lead:** Sample posts — placeholders for things I'd actually want to write about.

| Category | Title | Excerpt | Tags | Read time |
|---|---|---|---|---|
| design | Why one "accessible" label actively misleads people | A stop that works for a wheelchair user can be useless to a blind one. The case for per-profile scoring over a single binary flag. | RAG · accessibility | 8 min |
| evaluation | Building a reference-free RAG eval harness | How to measure grounding, entity recall, and hallucination without falling into the LLM-as-judge circular trap. | NLP · evaluation | 11 min |
| engineering | Graceful degradation when the LLM gets it wrong | Pairing a 70B intent extractor with a keyword-parser fallback so a voice booking never just fails on the user. | LLM agents | 6 min |

---

## 10. Contact

Three-column board. Left: the pitch and the button. Middle and right: plain
facts, the right column set flush right. No eyebrow, no form.

- **Heading:** Let's build something that matters. (closing period in accent)
- **Button:** Get in touch -> `mailto:khan.faizan@etu.unige.ch`
- **Under the button:** Created by + the signature

| Column | Group | Content |
|---|---|---|
| Middle | Location | Geneva / Delhi |
| Middle | Social | GitHub · LinkedIn (Simple Icons marks, logo and name only) |
| Right | Contact | +41 77 289 67 74 (`tel:`) / khan.faizan@etu.unige.ch (`mailto:`) |
| Right | Explore | About · Skills · Projects · Experience |

The header monogram fades out while this section is on screen and returns on the
way back up, so the same hand is not on screen twice. The menu button stays.

The signature is "Faizan" in Mrs Saint Delafield, converted to outlines with
fontTools so nothing is parsed at runtime. A wide stroke travels each glyph
outline inside an SVG mask and uncovers the filled letterform behind it, one
glyph every 0.2s, driven by `stroke-dashoffset`. It writes once, when the
section is reached; static under reduced motion.

---

## 11. Sign-off band

Decorative, `aria-hidden`. Full-bleed inside the page gutter, directly below the
contact section. No footer bar, no rule across the page.

- **Image:** `assets/band-fog.jpg` — a ridge dissolving into fog, Tyler
  Lastovich via Unsplash. Greyed, settled, and toned toward the page's own
  off-white with a `color` blend, so the plate belongs to the site rather than
  sitting on it.
- **No accent.** The accent is spent on the links and the timeline spine. A
  coloured slab at the end would be the loudest thing on a page that has been
  quiet for five sections; the close is ink on paper, like the hero.
- **Code overlay:** two monospace columns in ink, from the AIBILITY WebSocket
  handler and the accessibility scorer. Second column hidden below 760px.
- **Word:** CREATE, overprinted in ink at 62% with `mix-blend-mode: multiply`
  rather than flat alpha, which would grey it. Baseline runs past the bottom
  edge.
