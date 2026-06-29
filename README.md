# DungeonQuest

A browser-based text RPG with animated sprites built with HTML5 Canvas and vanilla JavaScript. Fight your way through four dungeon chambers, defeat increasingly powerful enemies, and clear the dungeon to claim victory.

🔗 **Live demo:** [dungeon-quest-pygame.vercel.app](https://dungeon-quest-pygame.vercel.app)

---

## Gameplay

You are a knight descending into a dungeon. Each room holds a new enemy blocking your path. Defeat all four to win.

**Rooms**

| Room | Enemy | HP | Attack |
|------|-------|----|--------|
| 1 | Goblin | 55 | 10 |
| 2 | Cave Troll | 95 | 17 |
| 3 | Dark Witch | 78 | 21 |
| 4 | Dragon | 145 | 29 |

**Actions**

- **Attack** — standard strike, 90% hit chance
- **Magic** — costs 10 HP, deals bonus damage, 97% hit chance
- **Rest** — skip your turn to recover 14–25 HP
- **Flee** — 45% chance to escape and restart

---

## Features

- Animated canvas sprites with idle, attack, hurt, and death states
- Flickering torch lighting with radial gradients
- Enemy walk-in entrance animation per room
- Particle effects for slashes, magic bursts, healing, and damage numbers
- HP bars with color-coded health states
- Scrolling combat log
- Four unique enemy types with distinct color and ear shapes

---

## Tech stack

- HTML5 Canvas 2D API
- Vanilla JavaScript (no libraries or frameworks)
- CSS custom properties for UI theming
- Deployed on Vercel (static)

---

## Run locally

No build step required — it's a single HTML file.

```bash
git clone https://github.com/<your-username>/DungeonQuest-pygame.git
cd DungeonQuest-pygame
open index.html
```

Or serve it with any static server:

```bash
npx serve .
# then visit http://localhost:3000
```

---

## Project structure

```
DungeonQuest-pygame/
├── index.html   # entire game (HTML + CSS + JS in one file)
└── README.md
```

---

## License

MIT — free to use, modify, and distribute.
