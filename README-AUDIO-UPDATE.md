# Audio update

Added synthesized sound effects using the browser Web Audio API, so the game does not need extra audio files or third-party downloads. Effects include strikes, aura blasts, dashes, jumps, charging, transformations, ultimates, weapon arts, taking damage, defeat, respawn, pickups, and boss victory.

Use the SOUND ON/OFF button in the game header to toggle effects. On Android, tap ENTER THE REALM once to allow the browser to activate audio. The service worker cache version was updated to `lwx-mobile-v4-audio` so the latest game files are fetched after deployment.

To publish the update, upload/replace the contents of this folder in the existing GitHub Pages repository and commit the changes.
