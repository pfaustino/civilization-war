# Civilization War — Architecture (full scope)

**Status:** Empty placeholder — GPLv3 license only. No README or source in repo.

## Intended direction

Civilization-style war / strategy sim (RTS or 4X — undecided). Listed as inactive prototype in portfolio metadata.

## Current repository contents

- `LICENSE` (GPL-3.0)  
- `ARCHITECTURE.md` (this file)  
- `docs/adr/` — decisions to record when project starts  

## Planned architecture (draft)

When scoped, expect:

```
Simulation core (turn or tick loop)
 ├── Map / territory grid
 ├── Faction + diplomacy state
 ├── Economy (resources, production)
 ├── Military (units, combat resolution)
 ├── Tech / civic progression
 └── UI layer (map, panels, minimap)
```

## Open decisions (ADR backlog)

1. RTS real-time vs turn-based  
2. Single-player first vs multiplayer  
3. Web (Canvas/WebGL) vs desktop (Godot/Unity)  
4. Scope: micro skirmish vs full civ campaign  

## Next steps

1. One-page design doc (win condition, core loop)  
2. Pick engine → ADR-0001  
3. Scaffold repo with `src/`, CI, minimal loop  

## Docs

`docs/adr/README.md`
