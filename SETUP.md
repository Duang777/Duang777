# Duang777 GitHub Profile Setup

This folder is ready to become the `Duang777/Duang777` profile repository.

## Install

1. Create a public GitHub repository named exactly `Duang777`.
2. Add `README.md` and the `.github/workflows` folder from this directory into that repository.
3. Commit and push to the `main` branch.
4. Open the repository Actions tab and manually run:
   - `Metrics`
   - `Contribution Snake`
   - `Profile 3D`

## Recommended Token

The metrics workflow can run with the built-in `GITHUB_TOKEN`, but a personal token gives better data coverage.

Create a classic PAT with `public_repo` scope, then add it as a repository secret named:

```txt
METRICS_TOKEN
```

## Notes

- The profile README uses public image services for the header, stats cards, typing text, and skill icons.
- Generated files appear after the workflows run.
- The contribution snake is committed back to the `main` branch under `dist/`.
- The 3D graph is committed back to the `main` branch under `profile-3d-contrib/`.
