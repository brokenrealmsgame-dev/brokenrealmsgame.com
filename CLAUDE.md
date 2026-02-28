# CLAUDE.md — BRVR Website Project

## PROJECT OVERVIEW
**Project:** BRVR Official Website
**Game:** BRVR — a physics-based VR action RPG (Unreal Engine 5.7, OpenXR)
**Developer:** Solo indie dev (Br)
**Website Purpose:** Steam page presence, marketing, community, press kit

This is a SEPARATE project from the game codebase. Website code lives here.

---

## GAME PROJECT (READ-ONLY REFERENCE)

The full game project is at:
```
C:\Users\Christoffer\Documents\Unreal Projects\BRVR\
```

**You have READ access to the entire game project.** Use it to look up:
- Game mechanics, stats, balance numbers
- Feature descriptions
- Code architecture (for technical blog posts)
- Any game detail you need for accurate website copy

**DO NOT write/edit any files in the game project.** Only read.

### Key Reference Files in Game Project:
| File | What It Contains |
|------|-----------------|
| `BRVR_GAME_DESCRIPTION_FOR_STEAMPAGE.txt` | **THE GOLDEN PATH** — complete game description with ALL systems, stats, numbers |
| `GAME_AUTHORING_PIPELINE.txt` | Vision doc, VFX templates, system roadmap |
| `STATUS.md` | Current development state |
| `FINDINGS.md` | Playtest observations, bugs, feature ideas |
| `CLAUDE.md` | Game project conventions and architecture |
| `Source/MyProject5/` | C++ source code for all game systems |
| `Content/` | Unreal Engine assets |

### Game Description Copy Lives Here Too:
`BRVR_GAME_DESCRIPTION_FOR_STEAMPAGE.txt` is copied into THIS project root for quick reference.

---

## THE SOUL OF THE GAME
> "I am flying, and I have a fireball in my hand."

Every design decision serves this feeling. Playtesters said they could "feel the love" in this game. The website should convey this same energy.

---

## GAME HIGHLIGHTS (For Website Copy)

### One-Line Pitch
A physics-based VR action RPG where you swing swords, hurl fireballs, brew potions, and battle through 5 procedurally generated levels of escalating danger.

### Key Differentiators
1. **Physics = Power** — Swing harder = more damage. Consistent across ALL weapons.
2. **Deep RPG in VR** — 5 talent trees, 5-tier weapon rarity, 20-character roster, milestones
3. **Accessibility First** — No bending, magic grab, toggle grip, wrist UI. Everyone plays.
4. **Roguelike Runs** — Procedural maps, random loot, random vendors. Character persists.
5. **Physical Crafting** — Throw flowers into a cauldron, grab the potion that launches out
6. **Hardcore Permadeath** — Optional permanent death for real stakes
7. **Physics Magic Combos** — Slam fireballs, draw apart, coat sword in fire, punch projectiles
8. **Solo Dev Passion** — "Feel the love" — handcrafted with care

### 5 Character Classes
Warrior, Ranger, Mage, Adventurer (recommended), GM (creative mode)

### Combat Systems
- Melee weapons (physics-based swing damage)
- Ranged guns (fireball, frostball)
- Magic combos (slam fusion, draw apart, throw load, fire coating)
- Shields (block + bash + ricochet)
- Fist combat
- 4 status effects (burning, cold slow, poisoned, rupture)

### 5 Levels
Tutorial Meadow → Jungle/Beach → Champion Arena → Hard Landscape → Boss Domain

### Tech Specs
- VR: 110-120 FPS stable on Quest + PC VR
- Map gen: 340ms per level
- Custom ECS-like enemy system (not UE5 Mass Entity)

---

## WEBSITE DESIGN PHILOSOPHY
- **Accessible** — the website should match the game's accessibility-first ethos
- **Passionate** — solo dev energy, not corporate. Authentic voice.
- **Visual** — VR games sell on visuals. Screenshots/video front and center.
- **Welcoming** — not gatekeeping. "Everyone plays."
- **Fast** — good Core Web Vitals, works on mobile

---

## WORKING PRACTICES
- Keep it simple — don't over-engineer
- User preference: provide paste-ready commands when possible
- Document decisions as we go
- Mobile-first responsive design
