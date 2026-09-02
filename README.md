# University Football combined datapack

Current pack version: **3**

The single pack University Football needs: every team name, every roster, every
team logo, and the stadium effect audio.

## Install

Open the game and **drag this repository's ZIP straight onto the datapack
panel**. You do not need to unzip it, and it works in any browser.

1. Click **Code**, then **Download ZIP**.
2. Drag the downloaded `.zip` onto the datapack panel in the game.

That's it. If you would rather unzip it first, drag the extracted
`ufb-data-pack-main` folder in instead — either works. There is also a browse
button, which uses a folder picker that only Chrome and Edge support; dragging
has no such limitation.

Everything is read on your own machine and stored in your browser. Nothing is
uploaded anywhere.

## What is in here

| | |
|---|---|
| `data/teams.json` | all 266 Division I programs |
| `data/rosters.json` | 26,144 players |
| `data/logos/` | team logos |
| `audio/` | stadium effect layers — crowd, cheers, pad hits, whistles, catch, throw, kick, QB cadences |

## Band music is not in this repository

Fight songs, third-down songs and menu themes are hundreds of megabytes of
commercial recordings, so they are not distributed here. **The game plays
perfectly well without them** — you get the crowd and the effects, and the
datapack panel simply notes which music layers are missing.

To add music, drop files into `audio/` before importing. The game selects
tracks by **filename**:

| filename pattern | what it is used for |
|---|---|
| `<School>,_<Song Title>.mp3` | that school's band music |
| `UFB_Theme_-_*.mp3` | menu music, one drawn at random each visit |
| `UFB_Anthem_-_*.mp3` | the stadium reveal, and the default third-down song |
| `UFB_Crowd_-_*.mp3` | looping crowd ambience |
| `UFB_Cheer_-_*.mp3` | crowd reactions on big plays |
| `UFB_Hit_-_*.mp3` | pad impacts |
| `UFB_Whistle_-_*.mp3` | the official's whistle |
| `UFB_Catch_-_*` / `UFB_Throw_-_*` / `UFB_Kick_-_*` | ball sounds |
| `UFB_Cadence_-_*.mp3` | quarterback cadence at the line |

Add as many files per prefix as you like — the game picks between them at
random, so more files means more variety.

A school's third-down song belongs to whoever is **on defense**: face third
down against Georgia and you get *Dies Irae*, against Florida State the
*War Chant*.

## Updating

Download this repository again and drag the new zip in. Career saves are not
deleted when a datapack is updated. The game checks the pack version on open
and warns when it is out of date.

Version 3 adds the stadium effect audio and the drag-and-drop install.
