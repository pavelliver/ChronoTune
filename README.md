# ChronoTune

A pass-the-phone music timeline game. Each turn plays a mystery song through Spotify; place it on your timeline by release year. First to the target number of songs in the right order wins.

- 2–4 players on one device, steals with tokens, bonus token for naming title and artist.
- 10,138 songs from 1955 to 2026, filterable by popularity and decade, plus your own Spotify songs.
- Installable: "Install app" in Chrome on Android, or Share → Add to Home Screen on iPhone.

Music plays through Spotify's embedded player: full songs when logged in to Spotify in the same browser, 30-second previews otherwise (always on iPhone).

## Files

| File | Purpose |
|---|---|
| `index.html` | The game |
| `songs.js` | Song deck: title, artist, original release year, Spotify track ID, popularity |
| `manifest.webmanifest`, `sw.js`, `icons/` | Home-screen install and offline start |

## Credits

Song list and original release years come from the open-source [sjmarais9/hitster](https://github.com/sjmarais9/hitster) deck, whose years are cross-checked against MusicBrainz.
