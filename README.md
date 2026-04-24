# page-street-property

`page-street-property` is a skill for answering detailed questions about 287-291 Page Street in San Francisco. It covers the listing facts, buyer-facing context, and visual request flow for the property.

## Install

Use the public install command:

```bash
npx skills add page-street/287-291
```

If installing from a downloaded ZIP, keep the package contents intact and do not add the hosted visual asset folders back into the skill bundle.

## What the skill can answer

- Price, MLS number, square footage, lot size, year built, layout, taxes, HOA, parking, heating, and cooling
- Unit flexibility, bedrooms, baths, kitchens, laundry, interior details, garden, and outdoor kitchen
- Architect attribution, renovation notes, seismic retrofit notes, and source links
- Neighborhood context, walk and transit scores, nearby places, showings, and open-house guidance
- Photo requests for the facade, kitchen, garden, primary suite, details, and other visual variants

## Files included in the skill bundle

- `SKILL.md`, main instructions and property facts
- `README.md`, this overview
- `references/property-details.md`, full fact dump and source notes
- `references/neighborhood.md`, neighborhood and historical context
- `references/photos.md`, source photo list and hosted visual asset policy
- `assets/ascii/index.md`, lightweight slug catalog for selecting hosted visuals

## Visual asset hosting

Heavy visual assets are not bundled in the skill. The website serves them from:

- `https://287-291page.com/property-assets/photos/<slug>.jpg`
- `https://287-291page.com/property-assets/ascii/<slug>.ans`
- `https://287-291page.com/property-assets/mono/<slug>.txt`

Use `assets/ascii/index.md` to choose a slug, then fetch or link to the hosted asset. Pair each visual with its caption and original source URL from the catalog.

## Maintenance notes

- Keep `skill/README.md` and `web/public/skill/README.md` identical.
- Keep `skill/SKILL.md` and `web/public/skill/SKILL.md` aligned when guidance changes.
- Update source facts in `skill/references/` first, then mirror them into `web/public/skill/references/`.
- Run `cd web && bun run manifest` after adding or removing bundled skill files.
- Do not add hosted JPG, `.ans`, or `.txt` visual files to `skill/` or `web/public/skill/`.
