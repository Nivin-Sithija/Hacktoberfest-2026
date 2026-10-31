# Original repository backups

Each `.bundle` preserves the original repository's Git refs and history, including extra branches and available pull-request refs. The matching JSON preserves exported issue, pull-request, and release metadata. These snapshots were captured before consolidation on 31 October 2026; they do not recreate GitHub settings, discussions, comments, release assets, or secrets.

Restore a Git backup with `git clone archives/Schedule-Up.bundle restored-schedule-up` (substitute the relevant filename).

The project folders contain the original default-branch files. Their commit histories are also joined into this repository's main branch. Original licenses remain inside the project folders. Nested GitHub workflows are retained as source files and do not run from the repository root.
