# @omgbase/oqx has moved

**OQX (omgbase Query eXpressions)** now lives in the omgbase monorepo:

**https://github.com/omgbase/omgbase/tree/main/packages/oqx**

Nothing about the package changed in the move (ADR-019 in omgbase's `docs/decisions.md`):

- the npm package is still **`@omgbase/oqx`** — `npm install @omgbase/oqx` — with its own version line (0.10.2 onward is published from the monorepo);
- it still has **zero runtime dependencies** and is usable without omgbase;
- the language, engine, and public API are unchanged.

This repository is kept as a read-only archive of the history through **v0.10.1** (the tags `v0.4.0`–`v0.10.1` live here). Please open issues and pull requests against [omgbase/omgbase](https://github.com/omgbase/omgbase/issues).

The last standalone README is available at [`v0.10.1`](https://github.com/omgbase/oqx/blob/v0.10.1/README.md).
