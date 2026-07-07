# ODOOM — OASIS-Powered Doom

**Find the Keycard · OASIS Omniverse**

ODOOM is a modified [UZDoom](../UZDoom) build integrated with the OASIS Omniverse. Classic Doom gameplay meets real-world GPS discovery — keycards, weapons and armour are hidden at GPS locations in real-world parks. Find them physically to unlock them in-game. AR demon combat coming in a future update.

## Core Concept

ODOOM bridges the gap between classic retro gaming and augmented reality:

1. **Real-world discovery** — keycards and weapon pickups are hidden at GPS coordinates in local parks and green spaces
2. **Classic Doom gameplay** — fully functional Doom engine (via UZDoom) with original or custom WAD support
3. **OASIS integration** — avatar SSO, karma for completing levels, NFT weapon skins, shared leaderboard
4. **AR combat** (coming) — use your phone camera to fight demons overlaid on real-world environments

## OASIS Integration

- **Avatar SSO** — log in with your OASIS avatar; progress syncs across devices
- **Karma rewards** — completing levels, finding keycards and defeating bosses earns karma
- **NFT weapons** — weapon and armour NFTs owned on-chain, usable across OASIS games
- **GeoHotSpots** — keycard locations registered in STARNET as OASIS GeoHotSpots

## Related Projects

- [`UZDoom`](../UZDoom) — the Doom port ODOOM is built on
- [`STARNET`](../STARNET) — the decentralized asset store where GeoHotSpots are registered
- [`OGEngineSite`](../OGEngineSite) — the shared game engine for all OASIS worlds

## Tech Stack

| Layer | Detail |
|---|---|
| Game Engine | UZDoom (GZDoom fork) |
| Site | Single-file `index.html` — inline CSS + vanilla JS |
| OASIS API | `@oasisomniverse/web4-api@2.0.2` via esm.sh |
| Fonts | Orbitron, Rajdhani, Share Tech Mono (Google Fonts) |

## Running the Site Locally

```bash
npx serve .
# or
python -m http.server 8080
```

---

*Part of the [OASIS Omniverse](https://oasisomniverse.one) · Built on UZDoom · Powered by OASIS Web4*
