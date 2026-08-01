# claude --dance

A tiny single-file pixel-art dance party. Claude, a t-rex, a train, a truck, a cat, a mysterious egg, and a triceratops arrive by backpack and get down. Everything — sprites, music, themes — is generated in the browser; no assets, no dependencies, one HTML file.

## Try it

Open `index.html` in any browser, or visit the live page (GitHub Pages).

- **Tap/click** — fireworks + a mexican wave down the line (watch the egg)
- **Drag a dancer** — reorder the line; flick upward to launch them
- **beat** — start the chiptune; taps are then judged against the beat (combo counter)
- **remix buttons** — house / trap / trance / country / 90s pop, each with its own world and synthesized kit
- **share** — copies a URL that reproduces your current setup
- **postcard** — saves the current frame as a PNG

## URL flags

The fake CLI prompt is real: `?with=trex,cat&remix=trap&beat&hatch=golden&theme=night`

- `with` — comma list of dancers: `claude,trex,train,truck,cat,egg,trike`
- `remix` — `house` | `trap` | `trance` | `country` | `pop`
- `beat` — start the music on first tap
- `hatch` — force the egg's outcome: `dragon` | `chicken` | `golden`
- `theme` — `day` | `sunset` | `night` (otherwise follows your clock)

The egg hatches into a pink dragon, a disco chicken, or (rarely) a golden dragon. The cat has opinions about all three.
