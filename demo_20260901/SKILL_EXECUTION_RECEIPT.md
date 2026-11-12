# Skill execution receipt — direction rebuild

**Date:** 2026-09-01  
**Reason:** the prior Demo was correctly rejected: planning notes alone did not establish that the required Skills had affected the page.

## finesse-ui — `craft` route executed

**Design Read:** local one-to-one dog grooming · calm studio with typographic confidence · `register=brand` · `SOUL=7 / SPECTACLE=4 / DENSITY=4` · `Hero Engine=CSS-only static editorial crop`.

The lazy category default is a pale sage pet-spa page with rounded paw cards, testimonial stars and generic soft luxury copy. It is rejected in favour of a **Cobalt Field Studio** soul: a cold mineral substrate, one cobalt action colour, large compact sans display type and a cropped grooming portrait that creates category recognition without passing off a concept image as customer work.

| finesse-ui output | Concrete implementation | File / selector |
| --- | --- | --- |
| Premium substrate: named, locked tokens | Mineral, Porcelain, Petrol and Cobalt are named design tokens; no pure black/white, a single cobalt accent, translucent rules. | `styles.css :root`, `--line`, `--cobalt` |
| Grain / layered depth | Static `feTurbulence` grain is a fixed, pointer-free layer over the page; Hero image, optical plane, caption and content have distinct layers. | `body::before`, `.hero__visual`, `::before`, `::after` |
| Type tension | Tight negative tracking and `.9` display leading contrast against restrained body copy. | `h1,h2`, `h1`, `.intro__copy` |
| CSS-only Hero Engine | Static asymmetric crop with cobalt optical plane and a factual category image. It is intentionally non-animated, so it remains whole under reduced motion. | `.hero__visual`, `.hero__visual::before`, `.hero__visual::after` |
| Layout diversification | Split Hero, label-and-statement intro, service rail plus portrait, proof interruption, then dark booking close. | `.hero`, `.intro`, `.services__body`, `.proof`, `.closing` |
| Anti-cheap implementation | No beige/brass default, no icon grid, no fake rating, no fake review, no glass card, no gradient text, no duplicated booking label. | `index.html`, `styles.css` |

## design-taste-frontend — redesign audit applied

The rejected first version was treated as a redesign, not a new template. Its concrete fixes are: visible `Independent concept preview` identity; removal of the unsupported “sent home feeling their best” result claim; local system fonts instead of a remote font dependency; no em dash; fewer micro-labels; one booking label (`Book on Fresha`) wherever the booking intent appears; and explicit `max-width:760px` collapse rules for every multi-column family.

The audit rejected the previous recurring small uppercase labels and equal-card presentation. The code now uses a single non-section preview status and a numbered service rail because the three services are a real ordered selection, not generic feature cards.

## media-use — local asset workflow executed

1. `resolve.mjs --doctor` ran. The optional HeyGen provider is unavailable and was **not installed or logged into**.
2. `--candidates` surfaced only unrelated NothingbutNails assets; none was reused.
3. `resolve.mjs --adopt --project demo_20260901` registered all four selected local assets in `.media/index.md`:
   - `image_001`: concept care visual
   - `image_002`: concept closing visual
   - `image_003`: concept hero visual
   - `image_004`: official Fluffandtuff Instagram profile image

This connects the existing source/hash and rights ledger to the actual rendered files. The approved usage boundaries in `IMAGE_LEDGER.md` remain unchanged.

## Static checks after rebuild

- `finesse-ui/scripts/detect.mjs --json index.html` → `p0: 0`, no findings.
- `finesse-ui/scripts/detect.mjs --json styles.css` → `p0: 0`, no findings.
- Manual source sweep: no remote font import, form, script, iframe, price, hour, rating total, credential claim, copied review, or customer-result claim.

## Remaining boundary

Static Skill checks do not replace fresh full-page desktop/mobile visual acceptance. `CLIENT-SHOWABLE DEMO` remains pending that independent visual decision.
