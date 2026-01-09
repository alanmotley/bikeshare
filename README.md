# Bikeshare Project (Git & GitHub Workflow Practice)

This repository is used to practice a realistic Git workflow: branching, committing, pushing, and merging.
The underlying code is a small Python CLI that demonstrates basic bikeshare-style data exploration.

## Project Goal
Explore bikeshare trip data by:
- selecting a city (example: New York City)
- loading a CSV file locally
- printing simple summary output

> Note: This repo is evaluated on Git/GitHub workflow, not Python sophistication.

## Files
- `bikeshare.py` — Python CLI script
- `new_york_city.csv` — **local-only** dataset (ignored by git)
- `.gitignore` — excludes CSV files and common junk

## How to Run
```bash
python bikeshare.py
```

## Git Workflow Used (for Udacity rubric)
- Default branch: `master` (or `main`)
- Feature branches:
  - `documentation` (README + code comments)
  - `refactoring` (code refactor with at least 3 commits)
- Merged both branches back into the default branch.

## Notes
- CSV data should never be committed to GitHub.

## Credits
- Udacity Git & GitHub course project template
