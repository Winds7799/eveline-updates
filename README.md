# Eveline: updates

Fixes and updates for Eveline, delivered to the game over the air.

`manifest.json` lists the latest patch for each build of the game, per
platform. The game reads it a few seconds after launch, downloads a newer
patch in the background and uses it from the next launch on.

Each patch in `packs/` is signed. The game checks the signature and the
file's SHA-256 before it uses a patch, and refuses anything else.
