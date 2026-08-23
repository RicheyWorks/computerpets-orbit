# Orbit design

Implement against this file, not folklore.

## Identity

- Product: **Orbit**
- Repo: `computerpets-orbit`
- Idea: Pet Space Explorer
- Genre: Sci-fi idle
- Engine: Vue / PixiJS
- Surface: `5173`

## Loop

Delve is dungeons. Orbit is the sky. Species with flight traits (Soar) travel faster. Reef pets hate vacuum — they need a habitat bubble from Hearth.

## Play beats

- Unlock systems on a Pixi map.
- Assign pets + travel time.
- Ore → forge stats for Arena/Siege.
- Flavor text from Lore, not NASA fanfic that breaks canon.

## Neighbors

- computerpets-delve
- computerpets-soar
- computerpets-quarry
- computerpets-minter (crafted gear)
- computerpets-hearth

## Failure doctrine

Assign a non-flight pet to vacuum without bubble → refuse. Idle tick missed → catch-up cap 8h so nobody parks a year.

## Hard rules

1. Minigames cannot mint or burn NFTs by themselves (Minter is the write path).
2. Stats come from lived overlay care + Dojo caps, not cash shop.
3. Species kits stay inside Lore. Illegal hybrids never spawn.
4. Fail soft: the desktop overlay process is not this process.
