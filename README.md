# Aleris_TheBatteofWestnoth

An 8-player multiplayer map for Battle for Wesnoth, built around a symmetric octagonal layout with a contested central stronghold — a King of the Hill style objective at the heart of the battlefield.

## Concept

Eight starting positions surround a single strategic point at the exact center of the map. Unlike a standard keep, this central zone isn't owned by anyone at the start — it's an open prize. Whoever pushes in and holds it gains a strong economic and positional edge, but sits exposed on every side, within reach of all eight rivals at once.

This turns the mid-game into a real decision: rush the center early for the advantage, or stay defensive and let someone else take the risk of overextending.

## Highlights

- **Balanced octagon layout** — 8 starting positions split into two symmetric distance rings from the map center (~48-50 and ~65-68 tiles), keeping early rush timing fair across all players.
- **King of the Hill center** — a contested strategic point in the middle of the map. Holding it is powerful, but it's exposed to every player simultaneously, so the risk scales with the reward.
- **Distinct biomes per region** — snowy north, desert and hills in the southwest (dwarven start), tropical wetlands in the southeast, temperate grassland at the core. Each starting keep matches its surrounding terrain.
- **97 villages** spread across the map for balanced economic access.
- **Large scale** (108x109 hexes) — built for big FFA or team battles, not 1v1.
- **Tested in local games against AI** to validate pathing, starting position fairness, and resource distribution.

## Player count

8 players (FFA or teams)

## Map size

108 x 109 hexes

## Installation

1. Download `war.map` (or the map's `.cfg` file, if included).
2. Copy it into your Wesnoth `userdata/data/add-ons/` or `editor/maps/` folder, depending on your setup.
3. Load it from the Multiplayer menu or the Map Editor.

## Feedback

Feedback welcome, especially on:
- Balance around the central point (is it too strong, too exposed, or about right?)
- Village distribution for the outer players

## About me 
I'm Felix Lahaie. I had a brain hemorrhage that left me disabled, but I still love creating.

## License
 GPL v2
