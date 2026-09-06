# Legacy HTML Review

Reviewed: 2026-09-06
Canonical production: `index.html`

## word_rescue_mission.html

Classification: superseded legacy candidate containing an older persistence flow

Compared with `index.html`:

- 37 lines added and 16 lines removed in the canonical version.
- The canonical version normalizes Firestore map keys to strings for `usedWords` and `reviewDeck`.
- It supports both older and normalized saved-data shapes while loading.
- Player state is reset only when the player name changes.
- Loading is awaited before navigation and a loading state prevents repeated starts.
- Returning-player detection no longer triggers an asynchronous load during initialization.
- No unique function was found only in the legacy file.

Recommendation: retain unchanged until save/load regression tests pass for new players, returning players, offline fallback, and cross-device restore. The canonical version contains the safer persistence design.

Decision: do not restore this file over `index.html` and do not delete it yet.

