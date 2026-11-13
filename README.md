# XMP SFX - shared library

**525 sounds reach everyone right now.**

- 525 of them travel inside the installer, so nobody downloads them twice.
- 0 were added here after the release; every panel downloads these on its next sync.
- 13 were switched off, so every panel drops them.

Every installed XMP SFX panel reads `library.json` from this folder: it says what to
download and what to let go of. The control room writes it (`node control/server.mjs`);
editing it by hand would be overwritten on the next publish.

Library version 6, updated 2026-11-13.
