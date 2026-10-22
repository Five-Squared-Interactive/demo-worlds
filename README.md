# demo-worlds

Walkable VEML 4.0 worlds served as static files from GitHub Pages, for the WebVerse demo.

Each folder is one world: `index.veml` (the document, no-cache) plus content-hashed `assets/`
(immutable). Produced by `veml-ingest --deploy` from the private workshop; never edited here by hand.

Open a world in the client: `https://worlds.worldhub.me/webverse/index.html#world-url=<this site>/<world>/index.veml`
(the world's address URL-encoded, e.g. `%2F` for `/`). The publish host serves the client's page at `/webverse/`;
the world stays here and is fetched directly (this site answers with `Access-Control-Allow-Origin: *`).
