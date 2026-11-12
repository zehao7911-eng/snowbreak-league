# Snowbreak League

An original voxel snowball competition for portrait phones. Solo against three AI rivals, not online multiplayer. Inspired by the material hierarchy and layered winter-world presentation of the user-selected Combos Minecraft Kart Rush reference; no reference source, characters, textures or audio copied.

## Play
Drag anywhere on the arena to move and pack snow. Release to automatically throw at the closest rival (gold marker). Tap for a quick throw; hold for a heavy throw that breaks cover. Collect a gift for three triple shots. First to the target wins; at timeout the highest unique score wins. Ties do not count as a cup win. Win to unlock the next of three arenas. Replays retain best medals.

Desktop: WASD / arrows to move, hold and release Space to throw, Escape to pause. Music begins after a start/resume gesture. The supplied video soundtrack is embedded in both offline entries; no network dependencies.

Open index.html or standalone.html directly, or host this directory on a static HTTPS server. Both entries embed all code and Three.js. English, portrait-first layout; landscape shows an orientation reminder. WebGL is required.

## GameWave
Official document rechecked November 12, 2026 (October 30 revision). Runtime-injected neonlib is optional. Actual match start/end and resumed play are connected. Only snowbreak-league-v1 is read locally; cloud envelopes are scoped to this game. Optional confirmed likes unlock a gold scarf, direct comments unlock gold impact fragments. Local flags are device scoped. No other game's localStorage is enumerated or uploaded.

Automated core/controller/SDK mocks are provided. Actual GameWave App import and physical-device tests have not been performed. Browser and publication evidence is recorded separately.

## Develop
Run `node build.cjs` to rebuild both offline entries; `node test.mjs`, `node sdk-test.mjs`, `node controller-test.mjs` to verify.

Original procedural voxel art and arena layouts. BGM extracted from the user-supplied video; see MUSIC-PROVENANCE.md. Three.js is MIT licensed; see vendor/THREE-LICENSE.txt.
