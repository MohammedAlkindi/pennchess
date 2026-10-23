# Penn Chess

A one-page website for Penn Chess, the chess club at the University of Pennsylvania. It is an early learning project, and the repository is archived.

## What the site contains

`index.html` is a single page with a fixed header and five full-screen sections:

- Hero: the club name and a one-line description of the team
- Mission: what the club offers players who want to improve
- Training: open play, tactical drills and match preparation
- Events: the weekly schedule (Tuesday club meeting, Friday blitz night, Sunday match prep)
- Join: a link to request membership

The Contact Team and Request To Join buttons are `mailto:` links. Each section has a background photo loaded from Unsplash. At 600px wide or less, the header hides its navigation links.

## Run locally

Open `index.html` in a browser, or serve the folder with the included Node server:

```bash
node server.js
```

Then visit http://localhost:3000. Set `PORT` to use another port. The server uses only Node's built-in modules, so there is nothing to install.

## Stack

- HTML and CSS, with no JavaScript on the page and no build step
- `server.js`, a static file server built on Node's `http`, `fs` and `path` modules
- The Rajdhani font from Google Fonts

## Status

Archived. The code is kept as a record of early work and is not maintained.

## License

MIT. See `LICENSE`.
