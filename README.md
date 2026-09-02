# University Football combined datapack

Current pack version: **2**

This is the single-folder pack for University Football. It contains team
names, complete rosters, and local team logos. Stadium audio belongs in the
same folder; it is not a second pack.

## Install

1. Click **Code**, then **Download ZIP**.
2. Extract the downloaded zip.
3. Open University Football in Chrome or Edge.
4. Put your locally owned stadium tracks in its `audio/` folder.
5. Click **Install / update combined pack** and choose the entire extracted
   folder—not its `data/`, `logos/`, or `audio/` subfolder.

If University Football displays an update warning, download this repository
again and merge its files into your existing combined folder. Keep the existing
`audio/` folder in place, then choose the combined folder again. Career saves
are not deleted when a datapack is updated.

The browser reads the files locally and stores them in IndexedDB. Nothing is uploaded.
The game reads MP3, M4A, OGG, or WAV files from `audio/`. A track with `Still Fly`
in its filename is used for menu music; team-named fight songs are matched to scoring
and home-defense third-down events.

Version 2 adds automatic version checks in the game. The game checks when it
opens and every five minutes, keeps a visible warning on screen, and prevents
starting a game with an outdated pack.
