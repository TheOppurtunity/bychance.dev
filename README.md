# bychance.dev

Personal website and project portfolio by Chance McDonald.

## Current Project: MCU Power Scale Tournament Bracket

A single-elimination tournament bracket featuring 128 Marvel Cinematic Universe characters — 64 heroes and 64 villains — ranked across six stats: Strength, Durability, Speed, Energy Projection, Combat IQ, and Read Time.

**Features**
- Three modes: Heroes only, Villains only, or all 128 combined
- First-round matchups sorted chronologically by MCU release date
- Hover over any Round 1 character to see their full stat breakdown and description
- Pick winners, undo picks, reset the bracket, or randomize matchups
- Character image support via a local `images/` folder

## Structure

```
index.html      — the entire app (self-contained)
images/         — character portrait images (jpg, named by character)
```

## Adding Character Images

Name image files in lowercase with underscores, e.g. `iron_man.jpg`, `black_widow_natasha_romanoff.jpg`. The app will load them automatically.
