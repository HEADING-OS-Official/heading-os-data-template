# HEADING OS — private data overlay

This is the **private data repository** for a HEADING OS workspace. It holds all
real data — CRM contacts, knowledge, generated outputs, operational threads, and
context — kept deliberately separate from the public engine clone (`.heading-os`).

The engine resolves this repo at runtime through the data-root seam
(`get_data_root()`), either via the `HEADING_OS_DATA` environment variable or by
finding this directory as a sibling of the engine clone.

**This repository is private and must stay private.** It is never published and
never made public. Do not commit secrets here either — credentials live in the
engine's gitignored `.env`, not in tracked data.

Created by `scripts/create-data-repo.py`.
