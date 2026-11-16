The brand is anonymous: the wordmark is `openloop` in lowercase, paired with a ring that has a gap (an open loop). Never add a personal name, photo or avatar. `openloop` and the sample project names (Ledgerline, Harbor, Tessera, Plainsight), contact addresses and chart data in the previews are placeholders to be replaced.

## Six directions, one content model

Directions A to D share the same seven sections in this order: hero, featured projects, AI experiments, expertise, notes, about and now, contact. Each direction is a theme in `tokens.json`, so switch theme to see the whole system change. Pick one direction for production; do not mix themes on a page.

| Direction | Theme id | Character | Preview |
| --- | --- | --- | --- |
| A · Editorial Minimal | `editorial` | Warm white, serif statement, index-style lists, hairlines | `HomeEditorial` |
| B · AI Research Lab | `lab` | Dark, abstract vectors, live trace and an interactive chart | `HomeLab` |
| C · Bento Product | `bento` | Modular tiles of unequal size, product-style hero | `HomeBento` |
| C2 · Bento Systems | `bento` | Technical variant of C: terminal, latency histogram, deploy heat grid, interactive agent trace player, stack matrix | `HomeBentoSystems` |
| D · Intelligent Editorial | `intelligent` | Essay pacing, long serif text, one drawn abstract figure | `HomeIntelligent` |
| E · Vectorlab Handbook | `vectorlab` | Technical publication: sidebar topics, search palette, architecture diagrams, code and terminal | `HomeVectorlab` |
| F · Vectorlab Journal | `journal` | Paper ground, serif masthead and headlines, asymmetric magazine layout, procedural scientific figures | `HomeJournal` |

## Direction E: Vectorlab Handbook

A separate studio identity (`Vectorlab`) built from its own brief, not a variant of A to D. It has nine sections: header, hero with terminal, start exploring, featured work with diagrams, experiments index, notes, technical stack reference, about, footer. Layout is a three-column shell: topic sidebar, content, and an on-this-page rail; below 860px the sidebar becomes a drawer.

- Blue (`accent`), green (`accent-2`) and orange (`accent-3`) are small category and status indicators only: AI topics and running experiments are blue, engineering and complete are green, tools and shelved are orange. Never set text in green or orange on `bg`.
- Set small secondary text in `ink-soft`, not `ink-muted`; the specified `#73777f` is about 4.4:1 on `bg`.
- Paths, ids, dates, tags and code use `vl-mono`; headings and body use `vl-sans`. Borders are 1px `line`; panels use `radius-sm` at most.
- Diagrams are 1px strokes with a coloured square per node, mono sublabels, and dashed lines for feedback or replay paths.

## Direction F: Vectorlab Journal

A second Vectorlab identity, written from a separate brief for a digital science journal; it does not extend E. Sections in order: masthead with issue information, lead story with a large figure, three featured research stories, six research sections, experiment log, engineering perspectives, searchable archive, about band, footer.

- The ground is `bg` paper. Double rules (3px then 1px, `ink`) open the masthead and footer; a 3px `ink` rule opens every section. Use thin `line` rules between rows.
- Headlines and titles are set in `jr-masthead`, `jr-headline` and `jr-title` (Fraunces); body in `intel-sans` via `jr-body`; dates, issue numbers, reading times and experiment parameters in `jr-meta` (DM Mono).
- Teal (`accent`), coral (`accent-2`), lavender (`accent-3`) and pale yellow (`accent-4`) are illustration grounds and category markers. Every marker square carries a 1px `ink` outline so yellow stays visible on paper. Never set text in coral, lavender or yellow on `bg`; text on a coral, lavender or yellow fill uses `ink`, text on teal uses `on-accent`.
- Figures are drawn, never photographed: contour maps, ribbon diagrams, curves and scatter plots in token colours, with mono axis labels, a numbered caption (`Figure 1`) and a stated n or data source. Draw each hero figure once on load.
- Experiment types map to markers: Evaluation teal, Observation coral, Finding lavender, Model note yellow.

## Exploration 2: Vectorlab F + G concepts

Five further complete homepages for Vectorlab, each a different layout language: Swiss Scientific Journal (`HomeSwiss`), Modern Research Observatory (`HomeObservatory`), Technical Field Journal (`HomeFieldJournal`), Computational Design Magazine (`HomeMagazine`) and Premium Knowledge Platform (`HomePlatform`). Their palettes live inside each preview, not in `tokens.json`, because the theme limit is reached. Read `exploration-2.md` for the identity, strengths, weaknesses, evolution path and the recommended two directions (C and A) for each.

## Rules shared by A to D

- Set text in `ink` or `ink-muted` on `bg` or `surface`. Use `accent` for links and the one memorable element per page; `accent-2` only for secondary marks. Text on an accent fill uses `on-accent`.
- Headlines are sentence case. No all-caps labels, no numbered markers except where the content is a real sequence, no gradients, no 3D, no stock imagery.
- Motion is one orchestrated moment on load (hero) plus responses to the visitor's action (hover, toggle, chart scrub). Respect `prefers-reduced-motion`.
- Body line length stays under 70 characters. Serif body gets at least 1.55 line height, sans body at least 1.5.
- Every interactive element shows a solid focus ring of 2px in `accent` offset by 3px; it holds 3:1 on every `bg` in every theme.
- Desktop first at 1120px content width; single column below 760px with 20px side gutters.

## Choosing between them

- Choose A when the writing is the product and the audience reads slowly.
- Choose B when the experiments are the product and the audience wants evidence.
- Choose C when the visitor should understand the range of work in ten seconds.
- Choose D when the tone should be calm and considered, closest to a research publication.
- Choose F when the work should read as a periodical: dated, numbered, illustrated and edited.
- Choose E when the audience will navigate, search and cite: a living handbook of notes, experiments and designs.

## Iconography

Only the open-loop ring (a 24px circle stroked at 2px with a gap at the top right). No icon font. Arrows in text are written as words, not glyphs.
