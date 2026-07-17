# wax-stack
Crate digging via the Internet Archive

A record player for the internet's attic. Crate Dig pulls random 78rpm records from the [Internet Archive's Great 78 Project](https://great78.archive.org/) and plays them on an animated turntable — no search, no algorithm, just digging.

**Live:** _add your GitHub Pages URL here_

## Features

- **Spin something** — pull a random 78 from over 400,000 digitized sides
- Animated turntable with tonearm drop, disc spin, and coast-down
- Genre and decade filters (AND-combined)
- Session history with back/next transport
- Permalinks (`?item=…&file=…`) and clipboard share
- Keyboard shortcuts: `Space`/`Enter` to play/pause, arrow keys for prev/next
- Record detail and about modals

## Running it

It's a single self-contained `index.html` — fonts, styles, and code all inlined. No build step, no dependencies, no backend, no API keys.

- **Locally:** open `index.html` in a browser
- **GitHub Pages:** push to a repo, then Settings → Pages → deploy from the main branch

Everything runs client-side against archive.org's public APIs. Nothing is stored or tracked.

## Credits

All recordings and metadata come from the [Internet Archive](https://archive.org/) and the [Great 78 Project](https://great78.archive.org/) — a community effort to digitize 78rpm records, preserving recordings from roughly 1898 through the 1950s. Support them.

Audio is streamed directly from archive.org; this project hosts no recordings.
