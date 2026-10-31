# Agent instructions

Project type: personal

Keep global workflow guidance outside this repository. This file contains only
repository-specific commands and boundaries.

## Project context

Commit Time Machine is a static browser application with an optional Node.js
CLI. The browser path must keep GitHub usernames and optional tokens local to
the user's browser.

## Verification

- Unit tests: `npm test`
- Local browser smoke: `python -m http.server 8000`

## Scope boundaries

- Do not add a backend or transmit GitHub tokens without an explicit product
  requirement and privacy review.
- Keep generated dependencies and local analysis output out of Git.
