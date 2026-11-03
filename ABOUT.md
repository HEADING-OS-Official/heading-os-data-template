# HEADING OS: private data repository

This is the **private data repository** of a HEADING OS workspace. It holds
your own data: contacts, knowledge, generated documents, threads and context,
kept separate from the engine clone (`.heading-os`), which holds code only.

The engine finds this repository at runtime (`get_data_root()`), through the
`HEADING_OS_DATA` environment variable or as the sibling directory of the
engine clone.

**Keep this repository private.** Never publish it and never push it to a
public remote. Do not commit secrets here either: credentials live in the
engine's gitignored `.env`.

Created by `scripts/create-data-repo.py`.
