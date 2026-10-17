# Setup
1. Create (or use) PUBLIC repository `kurohig24/kurohig24`.
2. Upload `README.md`, `assets/` and `.github/workflows/pacman.yml` preserving paths.
3. Under repository Settings > Actions > General, ensure workflows are allowed and the GITHUB_TOKEN may write contents if required. The workflow has `contents: write` permissions.
4. Go to Actions > Pac-Man Contributions > Run workflow. When completed, the `output` branch should contain `pacman-contribution-graph.svg`.
5. If the action upstream changes, update the workflow's generator reference and output path; external stat cards require their servers to be available.
