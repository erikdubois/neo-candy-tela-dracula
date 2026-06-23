# CLAUDE.md — neo-candy-tela-dracula

## Project overview

Standalone repo for the **neo-candy-tela-dracula** folder-icon theme — the same folder set as
`erikdubois/surfn-tela-dracula` re-based onto the neo-candy-icons fallback.

## Current state

Ships one theme: `usr/share/icons/neo-candy-tela-dracula/` — folders only. Packaged as `neo-candy-tela-dracula-icons-git`
(recipe in `~/KIRO-PKG-BUILD-ICONS/neo-candy-tela-dracula/`), `depends=('neo-candy-icons-git')`.

## Patterns & decisions

- Folders only; everything else inherits neo-candy-icons. `icon-theme.cache` gitignored.
  Payload reused verbatim from the Surfn counterpart; only Name/Inherits/dir name differ.
