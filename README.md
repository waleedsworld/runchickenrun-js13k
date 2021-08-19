# Run Chicken Run — archived third-party project

> **Archival note.** This repository is a preserved copy of an existing
> open-source game by **Martin Hentschel** ([@hemartin](https://github.com/hemartin)).
> It is **not** the work of this account. It is kept **private, for reference
> and study only**, with full attribution. See [`NOTICE`](./NOTICE) and
> [`LICENSE`](./LICENSE) for details.

## What this is

*Run Chicken Run* is a small HTML5 canvas game written in plain JavaScript,
created by Martin Hentschel as an entry to the
[2017 js13kGames competition](https://2017.js13kgames.com/) (games must fit in
a 13 kB zip). A chicken is lost in the woods with a fox on its tail — run as
long as you can and grab yellow grains to build up a score multiplier.

The game is built on **physicsplain**, Martin Hentschel's simple 2D JavaScript
physics library: <https://github.com/hemartin/physicsplain>.

## Original source

- **Upstream repository:** <https://github.com/hemartin/runchickenrun-js13k>
- **Author:** Martin Hentschel — GitHub [@hemartin](https://github.com/hemartin) / @hemasail
- **License:** MIT (Copyright © 2017 Martin Hentschel) — see [`LICENSE`](./LICENSE)

Please refer to the upstream repository for the canonical, maintained version
and any live demo.

## Repository layout

| Path            | Purpose                                                         |
| --------------- | -------------------------------------------------------------- |
| `js/`           | Game source, split by concern (physics, state, screens, main). |
| `test.html`     | Loads the un-minified `js/*.js` sources directly for testing.  |
| `index.html`    | Production page; expects a minified `rcr.js` bundle.           |
| `make.sh`       | Build script: minifies with `uglifyjs` and zips for js13k.     |
| `fav.gif`       | Favicon shipped with the game.                                 |
| `LICENSE`       | MIT license, © 2017 Martin Hentschel.                          |
| `NOTICE`        | Provenance and attribution for this archived copy.             |

## Attribution & credits

- Game, code, and assets: **Martin Hentschel** (MIT).
- Physics: **physicsplain** by Martin Hentschel.
- Palette originally chosen via [Paletton](https://paletton.com/).

All credit for the software belongs to the original author. This archive adds
only this README and the `NOTICE` file; the original 2017 commit history is
preserved unchanged.
