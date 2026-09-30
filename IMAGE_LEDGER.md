# IMAGE LEDGER

All finished visuals for **Our World** are original to this project.

## Visual labels
- **RECONSTRUCTION** — evidence-constrained scene of an unphotographed past environment/event.
- **SCIENTIFIC DIAGRAM** — explanatory schematic based on evidence/models.
- **MAP / TIMELINE** — original data-based visualisation.
- **ARTIST'S IMPRESSION** — used when important appearance details are uncertain.

## Generation rule

Before image generation, the factual brief must be complete.

### Required human gate
When the next book page requires a generated visual, the assistant must **stop the book loop before generation** and ask:

> **Trev/buddy, can you enable the image tool?**

Only after Trev explicitly enables/requests image generation should the next approved visual be generated.

The approval command can then simply be:

> **Create image.**

That means: generate the next approved image brief in this ledger. If the brief is not sufficiently constrained by evidence, do **not** generate it yet; research/fix the brief first.

After the image is approved, immediately return to the normal page/evidence/artwork/fact-check/commit loop.

## Visual register

| ID | Page(s) | Visual | Label | Facts that must be preserved | Uncertain / do not overstate | Brief | Generated | Approved |
|---|---:|---|---|---|---|:---:|:---:|:---:|
| IMG-001 | 002 | Earth as a single world in darkness | ARTIST'S IMPRESSION / COVER-STYLE | Recognisable Earth geometry; physically plausible lighting | Exact cloud pattern is illustrative | ⬜ | ⬜ | ⬜ |
| IMG-002 | 016–017 | Descent from surface light into abyss | RECONSTRUCTION | Light attenuation with depth; no fantasy bioluminescent overload | Specific organisms/location depend on chosen setting | ⬜ | ⬜ | ⬜ |
| IMG-003 | 019–020 | Hydrothermal vent ecosystem | RECONSTRUCTION | Vent structure, plume behaviour and organisms must match chosen modern vent type | Species mix must not combine incompatible regions/depths | ⬜ | ⬜ | ⬜ |
| IMG-004 | 023–026 | Mid-ocean ridge to subduction cutaway | SCIENTIFIC DIAGRAM | Divergent ridge, new crust, plate motion, trench/subduction geometry | Vertical scale must be clearly schematic | ⬜ | ⬜ | ⬜ |
| IMG-005 | 027–030 | Seafloor age -> ancient continental evidence transition | SCIENTIFIC DIAGRAM | Young seafloor vs much older continental mineral record | Avoid implying no oceanic fragments older than a single hard cutoff everywhere | ⬜ | ⬜ | ⬜ |
| IMG-006 | 029–030 | Zircon crystal as deep-time archive | SCIENTIFIC DIAGRAM | Crystal structure/scale and dating concept must be scientifically accurate | Colours in microscopic-style view may be false-colour and must be labelled | ⬜ | ⬜ | ⬜ |
| IMG-007 | 032–033 | Chapter transition: young Solar System / forming Earth | RECONSTRUCTION | Period-appropriate bodies/materials based on current Solar System formation models | No claim that scene is a literal view of one exact moment | ⬜ | ⬜ | ⬜ |

## File naming convention
`artwork/<chapter>/<IMG-ID>-short-description-vNN.png`

Example:
`artwork/00-prologue/IMG-003-hydrothermal-vent-v01.png`

## Caption rule
Every reconstruction caption must contain enough wording to prevent a reader mistaking generated art for a historical photograph or direct observation.
