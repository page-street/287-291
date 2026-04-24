# Photo source list

All source images come from the Jennifer Rosdail listing page at
https://www.jenniferrosdail.com/287-291-page-street/, which carries the full
gallery. Redfin hosts the same set behind its CDN
(https://ssl.cdn-redfin.com/photo/9/bigphoto/240/426123240_*.jpg) but blocks
automated downloads, so the Jennifer Rosdail URLs are the working source.

Visual asset files are website-hosted, not bundled in the installable skill
ZIP. Each slug has three hosted forms:

- `https://287-291page.com/property-assets/photos/<slug>.jpg`: original source JPG
- `https://287-291page.com/property-assets/ascii/<slug>.ans`: truecolor ANSI
  block art rendered by chafa
- `https://287-291page.com/property-assets/mono/<slug>.txt`: monochrome Unicode
  block art; plain text that renders inside agent chat UIs (Claude Code,
  opencode, etc.) where ANSI escape sequences get stripped

Captions, source URLs, and category tags for all slugs live at
`skill/assets/ascii/index.md`, which remains bundled as a lightweight catalog
so agents can choose slugs before fetching or opening hosted visual assets.

## Exterior and facade

| File prefix | Caption | Source URL |
|---|---|---|
| 01-exterior-entry-closeup | Close view of the facade, red front doors, entry stairs, and bay window | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/1.web_-1.jpg |
| 02-exterior-angle | Angled street view showing the detached side, stacked bays, and front entry | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/1a.web_-1.jpg |
| 03-exterior-wide | Wider street view showing the full facade and Laguna mini-park side | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/99.web_.jpg |

## Living room and parlors

| File prefix | Caption | Source URL |
|---|---|---|
| 04-living-room-fireplace-wide | Front living room with carved marble fireplace, bay window, and pocket doors | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/2.web_-1.jpg |
| 05-living-room-fireplace-detail | Close view of the carved marble fireplace mantle | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/2a.web_.jpg |
| 06-living-room-fireplace-angle | Angled living room view with fireplace and adjoining parlor visible | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/3.web_.jpg |
| 07-living-room-fireplace-parlor-doors | Living room view facing fireplace and paneled parlor doors | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/4.web_-1.jpg |
| 08-living-room-stair-view | Living room seating with pocket doors and staircase beyond | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/5.web_-1.jpg |
| 09-living-room-pocket-doors | Living room view through pocket doors into the adjoining parlor | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/6.web_.jpg |
| 10-living-room-bay-sofa | Living room sofa framed by the front bay window | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/8.web_-1.jpg |
| 11-living-room-through-pocket-doors | View from adjoining parlor back through pocket doors to the front living room | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/11.web_.jpg |
| 12-living-room-window-angle | Living room corner view with front bay window and stair hall door | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/9.web_.jpg |
| 13-living-room-fireplace-side | Side angle of living room showing sofa, fireplace, and bay windows | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/10.web_-1.jpg |

## Kitchen and dining

| File prefix | Caption | Source URL |
|---|---|---|
| 17-kitchen-island-hall-view | Upper kitchen island viewed from the hall | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/20.web_-1.jpg |
| 18-kitchen-island-dining | Walnut-topped kitchen island with dining room beyond | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/22.web_-1.jpg |
| 19-kitchen-viking-range | Viking range, stainless hood, white cabinetry, and dark counters | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/23.web_-1.jpg |
| 20-kitchen-island-wine-fridge | Kitchen island detail with built-in wine fridge and walnut counter | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/25.web_-1.jpg |
| 21-kitchen-range-wide | Wide upper kitchen with island, Viking range, built-in refrigerator, and white cabinets | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/28.web_-1.jpg |
| 22-kitchen-wide-refrigerator | Wide upper kitchen view with island seating, Viking range, sink, and built-in refrigerator wall | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/27.web_-1.jpg |
| 23-dining-room | Dining room with wood table, black chairs, large windows, and sculptural pendant | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/31.web_-1.jpg |

## Primary suite

| File prefix | Caption | Source URL |
|---|---|---|
| 24-primary-bedroom-vanity | Primary bedroom with vanity desk, sitting area, and doorway to the bathroom | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/47.web_-1.jpg |
| 25-primary-window-seat | Primary bedroom sitting area with bay window seat and bath doorway | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/45.web_-1.jpg |
| 26-primary-window-seat-closeup | Close view of the primary bedroom bay window seat with neighborhood outlook | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/46.web_-1.jpg |
| 27-primary-closets-fireplace | Primary suite with built-in closets, window seat, and decorative marble fireplace | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/50.web_-1.jpg |
| 28-primary-closets-fireplace-detail | Primary suite fireplace wall with custom closets and round mirror | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/51.web_-1.jpg |
| 29-primary-bedroom-fireplace-suite | Primary bedroom suite with fireplace, adjacent sleeping area, and large corner windows | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/38.web_.jpg |
| 30-primary-bath-double-vanity | Primary bathroom with double marble vanity, oval mirrors, and step-in shower | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/55.web_-1.jpg |
| 31-primary-bath-freestanding-tub | Primary bathroom freestanding tub with subway tile and dark upper walls | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/52.web_-1.jpg |

## Additional bedrooms

| File prefix | Caption | Source URL |
|---|---|---|
| 32-bedroom-white-bed | Upper bedroom with white bed, tall windows, and decorative wall mirrors | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/60.web_.jpg |
| 33-bedroom-white-bed-desk | Upper bedroom with white bed, desk, and tree-facing window | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/62.web_.jpg |
| 34-bedroom-red-pillows | Bedroom with gray upholstered bed, red pillows, and original ceiling medallion | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/78.web_.jpg |
| 35-bedroom-red-pillows-side | Side angle of bedroom with red pillows, closet doors, and two windows | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/80.web_.jpg |

## Circulation and service

| File prefix | Caption | Source URL |
|---|---|---|
| 36-skylight-detail | Round skylight and pendant light above the stair hall | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/58.web_-1.jpg |
| 37-upper-laundry-stair-landing | Upper laundry closet with washer and dryer beside the stair landing | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/71.web_.jpg |
| 38-upper-laundry-closeup | Close view of the upper laundry closet with Miele washer, dryer, cabinetry, and folding counter | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/69.web_.jpg |

## Lower unit

| File prefix | Caption | Source URL |
|---|---|---|
| 14-lower-living-room-wide | Lower-unit living room with red chairs, dark floors, bay window, and abstract art | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/72.web_.jpg |
| 15-lower-living-room-sofa | Lower-unit living room sofa wall with tan leather sofa and abstract artwork | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/75.web_.jpg |
| 16-lower-kitchen-breakfast-deck-doors | Lower-unit kitchen breakfast table looking through glass doors to the small deck | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/85.web_-1.jpg |

## Garden and outdoor kitchen

| File prefix | Caption | Source URL |
|---|---|---|
| 39-garden-deck-fire-pit-wide | Wide rear deck view with fire pit, built-in bench, grill area, and string lights | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/87.web_-1.jpg |
| 40-outdoor-kitchen-grill | Covered outdoor kitchen with Sedona grill, dining table, and quartzite counters | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/91.web_-1.jpg |
| 41-garden-deck-fire-pit | Rear deck seating area with fire pit, bench, trellis, and string lights | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/95.web_.jpg |
| 42-garden-deck-outdoor-kitchen | Rear deck angle showing fire pit, outdoor kitchen, and blue-gray rear facade | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/97.web_.jpg |
| 43-garden-fire-pit-closeup | Close view of the rear deck fire pit, built-in bench, planters, and privacy trellis | https://www.jenniferrosdail.com/wp-content/uploads/2026/04/98.web_.jpg |
