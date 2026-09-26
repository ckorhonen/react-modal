# React Modal Instructions

The accessible modal implementation is in `lib/`, with browser tests driven by `scripts/test` and examples served by `scripts/dev-examples`. Install dependencies with npm; `npm test` runs the configured single-run Firefox browser suite, so Firefox is a prerequisite. `npm start` is the example server for a requested visual interaction check.

Preserve `setAppElement`, keyboard and overlay dismissal, focus behavior, and default-style merging. Completion for a behavior change is the relevant test passing, or a precise legacy-toolchain blocker, plus a focused browser interaction check when the change affects accessibility or rendering.
