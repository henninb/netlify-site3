# netlify-site3

A vanilla JavaScript Spotify "Now Playing" app using the OAuth 2.0 PKCE flow. Deployed to `site3.bhenning.com` / `site3.brianhenning.com`.

## Features

- Spotify OAuth PKCE authorization (no backend required)
- Displays currently playing track via the Spotify Web API
- Vanilla HTML/CSS/JS — no framework

## Setup

1. Sign up at [developer.spotify.com](https://developer.spotify.com) and create an app
2. Set the redirect URI to your deployment URL (e.g., `https://site3.brianhenning.xyz`)
3. Update the client ID in `public/script.js`

## Running

```bash
./run.sh
```

## Deployment

Deploys to Netlify via `netlify.toml`. The redirect URI must match the Netlify deployment URL configured in the Spotify app settings.
