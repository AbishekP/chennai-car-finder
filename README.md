# Chennai Car Finder

**Live website: [abishekp.github.io/chennai-car-finder](https://abishekp.github.io/chennai-car-finder/)**

A single-page tool for choosing a new car in Chennai. It covers 86 cars (including 15 EVs) and about 1,200 variants with Chennai on-road prices. Use the live website above, or download the files and open `index.html` in Chrome or Edge; there is no build step and no server needed.

## What it does

- **Explore and filter:** filter by budget, car, variant, fuel, gearbox, body type, seats, safety, size, mileage, waiting time and any of 45 features. Filters are remembered, and "Copy link to this search" shares them.
- **Compare:** compare any number of variants side by side, reorder them by dragging, sort them by value, price, cost or safety, and exclude EVs.
- **Best value for me:** rank variants by a score built from weights you set (price, ownership cost, safety, features, space, performance, fuel cost, driving ease).
- **5-year cost and EMI:** estimates fuel or electricity, service, insurance, tyres and resale, plus a loan calculator.
- **Photos, colours and size:** click a car's photo for a full-screen gallery of exterior, interior, detail and boot photos, a photo in every colour, and a to-scale size drawing (side, front and parking-bay views) that can overlay any other car. Links go to the maker's official page and a 360° view.

## Files

| File | Contents |
|---|---|
| `index.html` | The app |
| `data.js` | All car data: prices, specs, features, mileage, offers, colours and links. Edit this file to update anything. |
| `specs.js` | Variant-wise ARAI and owner-reported mileage, ground clearance and extra features from CarWale's variant pages |
| `photos.js` | Gallery photo links (from CarWale's image galleries), one per camera angle |
| `videos.html` | Review videos for each car |

Prices, offers and waiting times are from October–November 2026 and change monthly. Treat everything here as a guide and confirm with the dealer. The Notes tab inside the app lists sources and how reliable each kind of data is.
