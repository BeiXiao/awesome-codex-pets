# Contributing

The fastest way to add a pet to this list is to **submit it on
[codex-pet.com/submit](https://codex-pet.com/submit)**. The submission form:

- Takes your sprite, runs the same validation the CLI uses, and stores it on the codex-pet CDN.
- Generates the thumbnail and per-pet detail page automatically.
- Adds the entry to this repo on the next sync.

Once your pet is approved on [codex-pet.com](https://codex-pet.com), it will:

1. Appear in the live gallery.
2. Be installable via `npx codex-pet-cli add <slug>`.
3. Get a row in the gallery table in this README.

## Why submit on the website instead of opening a PR?

The sprite goes through the same review pipeline as every other pet (checking
sheet dimensions, frame layout, file size, and content). Doing it through
[codex-pet.com/submit](https://codex-pet.com/submit) keeps everything
consistent and means you don't have to fork or rebuild anything locally.

## Reporting issues

Bug or broken thumbnail? Open an issue on this repo. Anything related to the
website, install flow, or animation rendering — please open it on the main
[codex-pet.com](https://codex-pet.com) GitHub repo so it ends up in front of
the right maintainers.
