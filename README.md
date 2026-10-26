# HEADING OS: data repository template

**This is a public, empty template. Never put your own data in it, and never fork it to hold your data.** A fork of a public repository is public.

HEADING OS keeps code and data apart. The engine (https://github.com/HEADING-OS-Official/heading-os) holds code only. Your contacts, knowledge, documents and threads live in a second repository of your own, which must be private.

You do not need to clone this template. The engine's installer creates your private data repository for you, with this same layout, through `scripts/create-data-repo.py`: as a private GitHub repository by default, or as a local repository only with `--local-data`. See the install guide: https://github.com/HEADING-OS-Official/heading-os/blob/main/docs/INSTALL.md

This template exists so that you can read what that repository will look like before you install:

- the subject folders, each holding a `.gitkeep` so git keeps it;
- `config/data-paths.yaml`, the registry of data addresses the engine reads;
- `.gitignore`, which keeps rebuildable files, secrets and unsent drafts out of history;
- `.schema-version`, the layout version the engine checks.

License: see LICENSE and NOTICE. The template is licensed under the same terms as the engine.
