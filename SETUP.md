# Publish the GitHub profile README

1. Open https://github.com/deatharoundthecorner/deatharoundthecorner.
2. Replace the repository's `README.md` with this package's `README.md`.
3. Upload `assets/cyber-banner.png` to the repository path `assets/cyber-banner.png`.
4. Create or replace `.github/workflows/snake.yml` using the workflow supplied here.
5. Commit all changes to the default branch (usually `main`).
6. In **Settings → Actions → General → Workflow permissions**, allow **Read and write permissions**.
7. Open **Actions → Generate contribution snake → Run workflow**. Wait for the run to complete and confirm that an `output` branch appears containing the generated SVG files.

The README's banner is a local repository image, so it does not depend on an external image host. The snake will not appear until the workflow has run successfully at least once. GitHub's own contribution calendar is shown separately below the profile README.

## Files

- `README.md` — the profile content.
- `assets/cyber-banner.png` — custom neon-green cyber banner.
- `.github/workflows/snake.yml` — contribution snake automation.
