Whenever you edit code, docs, tests, or package metadata, update `Changelog.md` in the same change.

Before changing long-wait/wake behavior, read `docs/IV-0001-long-wait-and-wake-control.md`. Before changing result bounds, logs, truncation, or TUI tool rendering, read `docs/IV-0002-output-lifecycle-and-rendering.md`.

Canonical verification:

```bash
npm test
```
