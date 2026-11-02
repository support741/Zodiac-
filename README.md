# Zodiac Battlegrounds

An original zodiac-themed arena fighting game prototype.

## Vision
12 zodiac fighters, each with a distinct combat identity, elemental abilities, and five evolution tiers: Warrior, Awakened, Celestial, Divine, Omega.

## MVP (Phase 1)
- Browser-playable real-time 2D arena prototype with two original fighters: Aries and Scorpio.
- Keyboard controls, mobile touch controls, movement, basic attacks, block, dodge, cooldown-based abilities, health and energy.
- Single-player versus deterministic, clearly labelled bot AI.
- Responsive interface and basic accessibility settings.
- No simulated multiplayer or fake matchmaking.

## Technical direction
- Base44 for application shell, accounts and persistent progression (subject to integration testing).
- Phaser for client-side gameplay, subject to Base44 build/runtime compatibility validation.
- PvP deferred until authoritative server and latency tests are complete.
- Roblox is a separate possible release target, not a Base44 export feature.

## Release gates
1. Prove a playable local combat loop.
2. Validate mobile performance and input latency.
3. Validate persistence and account permissions.
4. Design secure server-authoritative PvP separately.

## Security
No API keys or private assets in this repository. Require review before production deployment.

## Status
Planning / unverified prototype. No working game is claimed yet.
