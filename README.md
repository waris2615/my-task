# My Task - Website Niche Automation

This repository tracks 20 website niches that are automatically generated.

## How It Works

1. A cron job runs every hour
2. It finds the first unmarked niche
3. Creates a new GitHub repo for that niche
4. Builds a multi-page website with unique 3D design
5. Enables GitHub Pages to make it live
6. Updates this file with `done: true`

## Progress

| # | Niche | Title | Status |
|---|-------|-------|--------|
| 1 | clothing-store | Luxe Fashion | ⏳ |
| 2 | phone-accessories | TechGear Hub | ⏳ |
| 3 | kitchen-equipment | Chef's Kitchen | ⏳ |
| 4 | jewelry-store | Golden Gems | ⏳ |
| 5 | furniture-home | Modern Living | ⏳ |
| 6 | beauty-cosmetics | Glow Beauty | ⏳ |
| 7 | sports-gear | Peak Performance | ⏳ |
| 8 | pet-supplies | Paws & Claws | ⏳ |
| 9 | books-store | Chapter One | ⏳ |
| 10 | fitness-equipment | Iron Strength | ⏳ |
| 11 | baby-products | Little Sprouts | ⏳ |
| 12 | automotive-parts | AutoPro Garage | ⏳ |
| 13 | garden-tools | Green Thumb | ⏳ |
| 14 | music-instruments | Sound Studio | ⏳ |
| 15 | coffee-shop | Bean & Brew | ⏳ |
| 16 | eyewear-store | Clear View | ⏳ |
| 17 | luggage-bags | Travel Easy | ⏳ |
| 18 | art-supplies | Creative Canvas | ⏳ |
| 19 | organic-foods | Pure Harvest | ⏳ |
| 20 | gaming-accessories | Level Up Gaming | ⏳ |

## Automation

- **Schedule:** Every hour (cron: `0 * * * *`)
- **Script:** `/opt/automate-tasks/automate-niche.sh`
- **Owner:** waris2615
