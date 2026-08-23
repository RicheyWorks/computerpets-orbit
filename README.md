# Orbit

**Pet Space Explorer** — Idle star map: send pets to distant planets for ores used in gear.

Part of the [ComputerPets](https://github.com/RicheyWorks/computerpets) universe. Map: [computerpets-ecosystem](https://github.com/RicheyWorks/computerpets-ecosystem).

> Status: **design scaffold**. Gameplay contract is frozen. Engine choice is the one in the brief. Implementation comes next.

## Loop

Delve is dungeons. Orbit is the sky. Species with flight traits (Soar) travel faster. Reef pets hate vacuum — they need a habitat bubble from Hearth.

## Genre & engine

- Genre: **Sci-fi idle**
- Engine: **Vue / PixiJS**
- Stack: Vue 3 · PixiJS star map · idle expeditions · ores → gear crafting
- Default surface: `5173`

## How you play

1. Unlock systems on a Pixi map.
2. Assign pets + travel time.
3. Ore → forge stats for Arena/Siege.
4. Flavor text from Lore, not NASA fanfic that breaks canon.

## Talks to

- computerpets-delve
- computerpets-soar
- computerpets-quarry
- computerpets-minter (crafted gear)
- computerpets-hearth

## Failure doctrine

Assign a non-flight pet to vacuum without bubble → refuse. Idle tick missed → catch-up cap 8h so nobody parks a year.

Canon rules that never yield:

- 210 living kinds. No illegal hybrids.
- Overlay pets can get tired, sick, or hide. Tokens are not burned by a minigame.
- Desktop walk stays the main quest. Closing Orbit must leave Rui walking.

## Layout

```
computerpets-orbit/
  README.md
  LICENSE
  docs/DESIGN.md
  src/                implementation lands here
```

## Run (Windows)

```powershell
cd app; npm install; npm run dev
```

Meet Rui first via the [flagship start-here](https://github.com/RicheyWorks/computerpets/blob/main/docs/START-HERE.md). This game is optional.

## License

MIT. See [LICENSE](LICENSE).

---

*Two hundred ten living kinds. Keep them so a line does not go quiet.*
