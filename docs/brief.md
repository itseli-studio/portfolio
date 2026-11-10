# Portfolio website — brief

_Living document. Filled in during discovery; updated as decisions are made._

## Sources used so far
Google Drive (owner: Eli):
- "ItsEli.com Web Copy" (Dec 2024): copy of the current site
- "Itseli_Operating_Manual_V3" (May 2026): positioning, principles, 5P Framework, Customer Journey
- "Itseli" doc (Jun 2026): Brand Foundation / Strategic / Creative / Enterprise Partnership FAQs
- "Harmless Brand Identity Deck.pdf": case study material
- The live site (www.itseli.com) could not be fetched: the cloud environment's network policy blocks
  the domain. Add it to the environment's Allowed domains to review the live site.

## Current website
- URL: https://www.itseli.com/
- Voice: first person ("I"), freelancer framing ("Hey, I'm Eli, a freelance creative...").
- Pages: Home, Get to know me, View my work, Ready when you are (contact).
- Services listed: Brand Strategy, Visual Identity, Web Design, Product Packaging Design.
- What works: clear "clarity over noise" thesis; warm, human founder story; good lines
  ("The most successful brands aren't the loudest. They're the clearest.", "Ready when you are").
- What doesn't: positioned as a freelancer, which conflicts with the current model (retainer-based
  Clarity Partner with a team); offer is a list of deliverables instead of partnerships; case studies are empty.

## Company
- Name: itseli (written lowercase)
- Positioning: Clarity Partners™. "A subscription to clarity and direction." Not an agency, freelancer or studio.
- One-line description: A founder-led, retainer-based brand partner offering brand strategy, creative
  direction and design execution. We embed in businesses and continuously remove confusion.
- Mission: Build brands on truth, not perception. Bring clarity to businesses before they ask the world for attention.
- Purpose: People build things that don't work, then blame marketing, design or visibility, when the real issue is a lack of clarity.
- Location: Lakewood, NJ
- Contact: TBD

## Services (current offer structure)
> **Changing (2026-11-10):** Eli is rewriting Brand Foundation and the offer. A new studio doc
> (studio outline, process, philosophy) will replace this section. Don't build on the list below.

1. **Brand Foundation**: one-month fixed engagement. Discovery, stakeholder conversations, market
   observations, messaging exploration, recommendations, roadmap. The entry point.
2. **Creative Partnership**: ongoing execution (advertising, packaging, marketing materials, campaigns,
   sales collateral, website, signage, vendor artwork). Minimum commitment.
3. **Strategic Partnership**: ongoing strategic + creative leadership for growth, change, repositioning. Minimum commitment.
4. **Enterprise Partnership**: multi-brand / multi-location alignment, brand architecture, messaging systems.
- Pricing logic: Complexity + Scope + Impact.
- Responsible for: brand strategy, communication, visual identity, design execution.
- Not responsible for: business operations, product/service management, social media management.

## Method
- **5P Framework** (every client starts here): Purpose, Positioning, Persona, Promise, Proof.
- **Customer Journey**: Awareness, Consideration, Purchase, Experience, Retention & Advocacy.
- **Process**: Strategic Foundation, Unified Identity, Customer Journey Alignment, Ongoing Execution, Data-Driven Optimization.
- **Principles**: Business impact over aesthetics. Collaborative, not isolated. Growth-focused thinking. Strategy before execution.
- **Truths**: Clarity before creativity. Always. They build and leave, we build and stay.

## Projects / case studies
Client names from the current site's work page: Twisty, Squatz, Infinite Panels, Bun, Delcampo, Dive,
Fellowship, Harmless, JThyme, NBM, Pals, Pepe, PierPins, Pinch, Rightfully, Salt, Secure Entry, Tipmate,
Tudelu, Wave, Yapchik, Greenbowl.
- Harmless: brand identity deck exists in Drive (challenge: "Compromising safety for effectiveness").
- Case study write-ups still needed for the rest.

## Clients & testimonials
TBD

## Team
- Eli Weissman: founder, strategy and creative direction ("thinking layer").
- Sarah: studio operations / PCM.
- Designer(s).

## Brand
- Logo: TBD (need files)
- Colors: TBD
- Typography: TBD
- Tone of voice: plain, warm, direct, a little playful. Cut every extra word. The reader isn't stupid.

## Site goals & audience
- Audience: founders and businesses that want an ongoing partner close to the business.
- Goal: feel like a premium product, not a service provider. Calm, confident, patient, detailed:
  a therapy-like atmosphere. Inspirations: Notion, Airbnb, Apple.

## Pages / sitemap
Draft (search-first): Home (search) · Partnerships (Brand Foundation, Creative, Strategic, Enterprise) ·
Method (5P Workshop, Customer Journey) · Work (index + case studies) · Studio (Eli, team) · Book an intro ·
No-results state. Search answers common questions straight from the FAQs.

## Technical
- Hosting / domain: itseli.com
- Stack: TBD
- CMS needs: TBD

## Design concepts
- `docs/concepts/01-clarity-os.html`: "Clarity OS". The studio presented as a product: live 5P
  workspace as the hero, a breathing pause, process tabs, interactive customer journey, partnership
  "plans", a fit check, work library, founder note, intro form, ⌘K command palette.
  Artifact: https://claude.ai/artifact/XcbWKuxEPn7cJeCPTabMFg. **Rejected** (too dark and cinematic).
- Hero options canvas: https://claude.ai/artifact/Aw3oW7i1dBmyunUbUyxxDL. Six heroes in the itseli OS
  look: A Blank Page, B Spotlight (search), C Today (day view), D Your Portal (empty client portal),
  E One Task, F Unclear to Clear (board). Plus boards with 6 options each for buttons, navigation,
  inputs and cards.
- Same canvas, page "B · Spotlight": the chosen direction explored. Homepage takes B1 Search + preview,
  B2 Ask and get an answer (FAQ answers), B3 Nothing but the field, B4 Phone. Pages reached from search:
  Brand Foundation, The 5P Workshop, Harmless case study, Eli and the studio, All work, Book an intro
  dialog, No results state. The boards link to each other (Play to click through).

## Open questions
- Switch voice from "I" to "we" across the site? (Concept 01 uses "we", with a first-person founder section.)
- Show prices or keep "Complexity + Scope + Impact"?
- Which 4–6 projects become full case studies first?
- Real photography of Eli and the studio?

## Decisions
- 2026-11-03: Concept 01 (Clarity OS) rejected: too dark and cinematic. Go back to emptiness and
  eeriness. Show options for the hero and UI elements only, not full pages.
- 2026-11-03 (**reversed 2026-11-10**): Take UI inspiration from Eli's own itseli OS app and its client portal
  (repo itseli-studio/itseli-os; see its docs/STYLE_GUIDE.md): monochrome black/white/greys, Inter,
  the black "it" tile mark, 1px lines, 1.5px icons, radii 8/10/12/16, color only for status meaning.
  Light theme only.
- 2026-11-03: Eli picked hero B (Spotlight): a search-first site where ⌘K search is the navigation.
  Explore that direction across the other pages.
- 2026-11-03: Redesign from scratch. Direction: the site should look and behave like a SaaS product
  (Notion / Airbnb / Apple influence), minimal, high-end, calm.
- 2026-11-10: Dropped the itseli OS look. Take no inspiration from Eli's other Claude projects
  (itseli OS, client portal, finances, Tribal prototype). The Spotlight boards' styling came from
  itseli OS, so only the search-first idea carries forward, not their look.
- 2026-11-10: Brief for the design: think like an elite brand developer who specializes in clear,
  honest communication. A VIP experience: modern, easy to navigate, and quick to get people to the
  answers most of them want.
- 2026-11-10: Brand Foundation and the offer are changing. Eli will share a detailed studio doc
  (outline, process, philosophy) to build on; it becomes the source of truth for content.
