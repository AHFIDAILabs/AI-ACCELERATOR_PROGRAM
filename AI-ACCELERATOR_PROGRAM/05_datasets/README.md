# Datasets

Use this folder to store datasets used in labs/projects.

## Conventions

- `raw/`: original data as received (often large)
- `processed/`: cleaned/transformed data generated from raw
- `external/`: third-party datasets where you store *links and license notes* (prefer not committing large archives)
- `sample/`: small sample datasets that are safe to commit to git

## Recommended practice

- Prefer committing only samples (for quick start) and provide download scripts/links for full datasets.
- If you must upload full datasets into the repo, ensure:
  - licensing allows redistribution
  - no sensitive/PII data is included
  - file sizes won’t exceed your Git hosting limits
