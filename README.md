# Deffe project export

This export is meant for advanced workflows such as local development, migration, or version control.

## Important

- Paid Deffe memberships already include hosting and HTTPS.
- For most projects, the easiest path is to keep publishing directly in Deffe.
- This archive contains project files and a schema-only SQL export. No database rows are included.

## Contents

- `project-files/` – the project files from your Deffe workspace
- `database/schema.sql` – database structure only (tables, indexes, constraints, routines/triggers when available)
- `deffe-export.json` – machine-readable export metadata

## Security and exclusions

- `.env` is excluded
- `.deffe/` is excluded
- `.git/` is excluded
- `vendor/` and `node_modules/` are excluded
- Laravel runtime cache/log directories under `storage/` are excluded
- Common local SQLite database files are excluded

## Git / GitHub

Git and GitHub sync are intended to build on top of this export flow. In Deffe, publishing directly is still the recommended default.

Project: **Excelência Agropecuária Angolana**
