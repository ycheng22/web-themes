# Exploration 2: Vectorlab F + G concepts

Five complete desktop homepages for Vectorlab, an independent AI engineering research studio and technical publication, each combining the Research Engineering Handbook with the Digital Science Journal. They share content (nav, hero line, the featured study "Beyond the Prompt: Building Reliable Agentic Systems", five topics, four experiments, engineering notes, archive, about) and differ in structure and visual language. Previews are under the card group "Exploration 2: F+G concepts".

The system allows eight themes and all are used, so each concept defines its palette inside its own preview and reuses the system's font families. Promote the chosen direction to a theme when it is taken to production. All figures are procedural placeholders; every number is sample content.

## A. Swiss Scientific Journal (`HomeSwiss`)
Palette: ivory `#f3efe3`, black `#151515`, ultramarine `#2338e0`, vermilion `#e5481f`. Type: Hanken Grotesk at 800 for headlines, DM Mono for metadata.
- **Identity:** a printed journal rendered precisely. An 8px top rule, issue numbers, one huge headline, geometric compositions (disc, quarter circle, vector field, arcs).
- **Journal and handbook:** the journal leads through headline scale and the featured abstract. The handbook shows in the agent-loop diagram, the topic strip with counts and the ruled, filterable archive.
- **Strongest:** timeless and sophisticated; hierarchy is unmistakable; scales well because everything sits on rules.
- **Weakest:** least approachable for first-time visitors; a modular grid needs discipline from every later author.
- **Evolution:** article template with a marginal figure column, issue pages as covers of the grid, archive by volume and issue.

## B. Modern Research Observatory (`HomeObservatory`)
Palette: warm gray `#eeede9`, deep blue `#0b2470`, cobalt `#1f4fe0`, cyan `#0e9db9`, orange `#ee8426`. Type: IBM Plex Sans Condensed and Plex Mono.
- **Identity:** an instrument panel. The nav is an axis with tick marks, the hero is a live vector field with a crosshair readout, topics sit on a scatter map, the archive is a heat grid.
- **Journal and handbook:** large research headlines on a dark lead panel; navigation by position and density rather than lists.
- **Strongest:** the most memorable hero; navigation itself is data; strong at conveying scale of the archive.
- **Weakest:** the topic map and heat grid need real data and care to stay honest; less readable for plain list browsing; heaviest to build.
- **Evolution:** a map view of all topics, density filtering of the archive, per-experiment live plots.

## C. Technical Field Journal (`HomeFieldJournal`)
Palette: paper `#f5f3ec`, graphite `#2b2d2f`, green `#3f6b4f`, orange `#c8601b`, blue `#2f5f9e`. Type: Fraunces, Public Sans, DM Mono.
- **Identity:** an engineering notebook kept in public. Sticky numbered index, title block (volume, issue, updated), margin annotations in italic serif, dark code excerpts, stable identifiers such as VL-0412, paper grain.
- **Journal and handbook:** the most even balance. The lead entry reads as an article (abstract, serif headline) and as documentation (code, method, dataset and result in the margin).
- **Strongest:** authentic and credible; the index sidebar and identifiers scale to hundreds of entries; easiest to author and maintain.
- **Weakest:** the sidebar costs width on small screens (it collapses to a top index); less dramatic visually than B or D.
- **Evolution:** per-entry pages with the same index pattern, a changelog and corrections log, entry statuses (draft, replicated, superseded), citations and data downloads.

## D. Computational Design Magazine (`HomeMagazine`)
Palette: warm `#efeae0`, ink `#1a1816`, pink `#e0457b`, cobalt `#2b3bd6`, lime `#c9e04a`. Type: Bricolage Grotesque with Instrument Serif italics.
- **Identity:** a generative-art publication. Phyllotaxis network hero, oversized type, a full-bleed dark lead story, offset coloured plates.
- **Journal and handbook:** strongest editorial voice; the handbook is reduced to a filterable archive and tags.
- **Strongest:** the most distinctive and artistic; best for stories and for press.
- **Weakest:** needs a generated image per article; oversized type and asymmetry strain at hundreds of items; weakest for look-up.
- **Evolution:** use as a feature layer on top of a calmer index, with generative covers per article seeded by its data.

## E. Premium Knowledge Platform (`HomePlatform`)
Palette: neutral `#fafafa`, ink `#0e1116`, violet `#5b34e8`. Type: Geist and Geist Mono.
- **Identity:** a product-grade knowledge site. Command-palette search, tabbed topic navigator, switchable featured chart, sparkline experiment table, faceted archive.
- **Journal and handbook:** the handbook leads (navigation, tables, facets); the journal is carried by the featured article and note cards.
- **Strongest:** best usability and scalability; responsive by construction; credible to engineers.
- **Weakest:** the least distinctive; closest to the products it is inspired by; editorial voice is thin.
- **Evolution:** the template for search, topic and archive pages regardless of which look is chosen.

## Recommendation
1. **C, Technical Field Journal.** It is the only concept where the journal and the handbook are equal, it has the most credible identity for an independent studio that publishes its data, and its numbered index and stable identifiers are what a site with hundreds of entries needs.
2. **A, Swiss Scientific Journal.** It is the strongest pure editorial identity and the best companion for a publication that wants to be read as a journal: timeless, precise and cheap to scale because it is built from rules and type.

Take C as the structure of the site and A's headline scale and geometric figures for the home and issue pages. Borrow E's command-palette search and faceted archive for both, and keep D's generative covers for occasional feature stories. B is the most striking but is better as a section (a topic map) than as the whole site.
