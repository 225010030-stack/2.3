# SSC Workbench (No IOA)

Standalone frontend clone for sharing and demo use.

## Scope

- No SSO / No IOA authentication code
- Pure frontend interactions with localStorage persistence
- Supports optional backend calls:
  - `POST /api/orchestrate`
  - `GET /api/agent-registry`

## Local run

Run from this folder with any static file server, for example:

```bash
python3 -m http.server 18181
```

Then open `http://127.0.0.1:18181/no-ioa.html`.

## Publish

Push this folder as a separate GitHub repository and enable GitHub Pages.
