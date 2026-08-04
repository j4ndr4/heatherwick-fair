# The Fair

A browser role-playing game inspired by *Scarborough Fair / Canticle* (Simon & Garfunkel).

You play **Elspie**, who receives a voyager’s letter and must gather **parsley, sage, rosemary, and thyme** across the bay of *NVTIM ESR.*

## Part 1 — Herb loop

1. Dawn at the cottage — the letter arrives; Mother sends you out.
2. Travel the map: Fair, Tavern, Port, Churchyard, Forest, Strands, Hill.
3. Move with arrow keys (or WASD); press **Space** near people or herbs.
4. Collect all four herbs — the letter reveals the next riddle line.

## Run

```bash
npm install
npm run dev
```

Then open the URL Vite prints (default `http://localhost:5173`).

## Controls

| Key | Action |
|-----|--------|
| Arrow keys / WASD | Move Elspie |
| Space | Interact / collect |
| M | Map |
| L | Letter |
| I | Satchel |
| Esc | Close panel |

## Stack

- Vite + TypeScript
- Canvas 2D locations
- Vanilla DOM UI (map, dialogue, letter, inventory)

## Source notes

Story, locations, and design notes live in `history.txt`. Art assets are under `assets/` (copied into `public/assets/` for the web app).
