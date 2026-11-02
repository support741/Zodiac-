# Architecture v0.1

## Client
Base44 application shell + isolated Phaser game canvas (integration unverified). Keep combat frame loop and hit detection independent of database/network requests.

## Gameplay
State machine: idle, move, attack, block, dodge, hitstun, knockout. Fixed simulation step, input buffering, cooldowns, attack hitboxes, stamina/energy, deterministic bot AI. All gameplay constants stored in versioned data.

## Persistence
Profiles, selected zodiac, progression and cosmetic unlocks. Treat client-supplied scores as untrusted; do not use them for competitive leaderboards.

## Multiplayer roadmap
Use server-authoritative combat with validation, reconnect handling, abuse controls and measured latency. Do not advertise competitive real-time PvP until tested.

## AI development workflow
GPT-6: specification and integration review. Claude: optional implementation reviewer via separately configured API. Gemini: optional independent QA via separately configured API. None of these external model connections are currently implemented. GitHub issues and pull requests are the source of truth; changes require tests and human approval.

## Intellectual property
Original zodiac characters, moves, UI and audio. Do not copy Mortal Kombat names, assets, finishing moves or character designs.
