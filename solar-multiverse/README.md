# Solar Multiverse

An interactive 3D solar system with six themed universes and three battle
simulators. One page, zero dependencies, runs entirely offline.

## Run it

Just open `index.html` in any browser — double-clicking it works.
Everything (the 3D engine, textures, models) is local to this folder.

If you'd rather serve it (e.g. to open it from your phone on the same
network), run either of these from this folder and browse to it:

    python -m http.server 8000        # http://localhost:8000
    npx serve                         # if you have Node

## The six universes (tabs at top-left)

| Tab     | World                                              | Your ship            |
|---------|----------------------------------------------------|----------------------|
| Expanse | UN Earth, MCRN Mars, OPA Belt stations, Ring gate  | Rocinante            |
| Trek    | Sector 001, Utopia Planitia, Spacedock, wormhole   | Federation cruiser   |
| Wars    | The Death Star replaces the sun                    | T-65 X-Wing          |
| Neon    | Cyberpunk grid — corp arcologies, data havens      | Smuggler dart        |
| Retro   | 1950s atomic-age pulp                              | Chrome rocket        |
| Chaos   | Rainbow nebulas, the Cursed Potato                 | Flying saucer        |

## Controls

**Nav view** — drag to look, pinch/scroll to zoom, tap any body for a
detail scan (drag to rotate it, pinch to zoom). Bottom bar: quick-select
pills, pause, orbit-speed slider, labels, gyroscope look (phones), reset.

**Flying (🚀 button)** — drag to steer, `↑`/`W` burn, `↓`/`S` retro,
`Shift` boost, `X` flip & burn brake, wheel/pinch camera. On phones,
hold the buttons on the right.

**Battles** (Expanse / Trek / Wars only):

- `Space` (or ✦ FIRE): PDCs / phaser beam / X-Wing lasers
- `T` (or the ◎/☢ button): nuke strike from Earth / photon torpedo /
  proton torpedo
- **Expanse** — MCRN hunters launch from Mars and hunt you with guided
  missiles; call nuclear strikes from Earth (watch the ETA, watch the
  blast radius). Endless waves.
- **Trek** — Borg cubes crawl toward Earth with sphere escorts. Kill the
  fleet before a cube reaches Earth or it's assimilated.
- **Wars** — fight through TIEs and Star Destroyers, follow the yellow
  exhaust-port bracket, and when it locks red: trench run. Put a torpedo
  in the port and enjoy the flyaway.

Tip: in the Expanse, tap the Mars pill *before* hitting 🚀 to spawn in
the middle of the hunter launch zone.
