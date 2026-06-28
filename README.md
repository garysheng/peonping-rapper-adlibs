# rapper_adlibs — Rapper Ad-Libs

A [peon-ping](https://github.com/PeonPing/peon-ping) / CESP v1.0 sound pack of **153 rapper ad-libs** from **42 of hip-hop's biggest names**, mapped onto your coding agent's events. Every session start, task completion, error, and approval prompt fires a different rapper's ad-lib at random.

## What's in it

A curated cut of the [therapboard.com](https://therapboard.com) soundboard — 42 marquee artists (2Pac, JAŸ-Z, Eminem, Snoop Dogg, Drake, Kendrick Lamar, Lil Wayne, 2 Chainz, DJ Khaled, Gucci Mane, and more), with their signature ad-lib clips. The 153 clips are spread evenly across the six CESP event categories (~25 per category), so every event has a deep random pool and you rarely hear the same ad-lib twice in a session.

## Install

```bash
# from a local clone
peon packs install-local /path/to/rapper-adlibs
peon packs use rapper_adlibs

# preview it
peon preview                 # plays the session.start ad-libs
peon preview task.complete   # plays the completion ad-libs
peon preview --list          # lists all categories
```

## Credits

All ad-lib clips are sourced from [therapboard.com](https://therapboard.com). Each clip is the property of its respective artist and rights holder.

## License

`fair-use`. Short ad-lib clips sampled from copyrighted recordings, included for personal, non-commercial use only as event sounds. All ad-libs remain the property of their respective artists and rights holders. Not for redistribution or commercial use.
