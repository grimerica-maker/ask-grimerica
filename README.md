# Ask Grimerica

Search what was said on The Grimerica Show. Each result is a roughly one-minute passage with a link that opens the episode on YouTube at that moment.

- Search only: nothing is sent to an AI model and no answers are written.
- The index is built from YouTube auto-captions of the public episodes. Members-only episodes are not included.
- The `ask.db.*` files are the search database in pieces; the page reads only the parts a search needs.
- `sqljs-httpvfs.js`, `sqlite.worker.js` and `sql-wasm.wasm` are sql.js-httpvfs (Apache-2.0), which runs SQLite in the browser.

To update: rebuild the database from the transcripts and replace the `ask.db.*` files and `config.json`.
