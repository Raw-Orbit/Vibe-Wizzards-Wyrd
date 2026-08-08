# Copilot Instructions for iam-universe

## Project status

This repository is in an early "Genesis / Research Framework" stage (see
`README.md`). At present it contains only project metadata (README,
`.gitattributes`) and no source code, build system, or dependency
manifest. Do not assume a language, framework, or directory layout exists
until you have checked the current tree — the codebase can look
completely different from one change to the next while it is being
bootstrapped.

## Working in this repo

- Before writing code, check `README.md` and the repository root for the
  current scope and structure — do not assume prior context still holds.
- There is no established build, lint, or test tooling yet. If you add
  code that introduces one (a package manifest, Makefile, Cargo.toml,
  etc.), also add the minimal instructions or scripts needed to build and
  test it, and mention them in `README.md`.
- Keep changes scoped to what is requested. Since the project has no
  existing conventions yet, avoid introducing large frameworks,
  multi-language rewrites, or speculative architecture in a single change
  — prefer small, reviewable steps that establish one convention at a
  time.
- Preserve the project identity in `README.md` (name, origin, author,
  status) unless a change explicitly asks to update it.
