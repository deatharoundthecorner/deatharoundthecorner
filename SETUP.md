# GitHub profile setup

This kit is designed for the GitHub account `deatharoundthecorner`.

## 1. Create or open the profile repository

GitHub displays a profile README when the repository is **public**, its name exactly matches your username, and it contains a non-empty `README.md` in the repository root.

Open <https://github.com/new> and create a public repository named:

`deatharoundthecorner`

If that repository already exists, use it instead of creating a second one.

## 2. Copy the kit into the repository

Extract this ZIP file. It contains:

```text
README.md
SETUP.md
assets/
  cyber-banner.png
.github/
  workflows/
    snake.yml
```

The easiest safe method is to clone your profile repository, copy these files into the cloned folder, then commit and push:

```bash
git clone https://github.com/deatharoundthecorner/deatharoundthecorner.git
cd deatharoundthecorner
```

Now copy `README.md`, `SETUP.md`, the `assets` folder, and the `.github` folder from the extracted kit into this cloned repository. Allow `README.md` to be replaced if Git asks.

Then run:

```bash
git add README.md SETUP.md assets/cyber-banner.png .github/workflows/snake.yml
git commit -m "Add cyber-themed GitHub profile"
git push
```

If you already have a local clone, do not clone again; just copy the kit files into that clone and run the final three commands.

## 3. Enable and run the contribution snake

1. Open the repository on GitHub.
2. Go to **Settings → Actions → General**.
3. Under **Workflow permissions**, select **Read and write permissions** if it is not already enabled, then save.
4. Open the **Actions** tab.
5. Select **Generate contribution snake**.
6. Click **Run workflow** and run it on your default branch (normally `main`).
7. Wait for the run to finish successfully. It will create/update an `output` branch containing the SVG files.

The workflow also runs daily on a schedule. GitHub may delay scheduled runs during busy periods.

The README's snake image may appear broken until the first workflow run completes and creates the `output` branch.

## 4. Check the profile

Open <https://github.com/deatharoundthecorner>. The README should appear at the top of the profile. Refresh after the first workflow run if the snake image is not visible yet.

## 5. Personalise before publishing

- Keep only the languages and tools you have actually used or are actively learning.
- Make sure the LinkedIn URL and email address in `README.md` are still the contact details you want public.
- Add links to other projects only when their repositories are public and ready to show.
- Pin your strongest 3–6 repositories on your GitHub profile.

## Notes

- The cyber banner is stored locally at `assets/cyber-banner.png`; it does not depend on an external image host.
- The typing effect, statistics cards, language icons, and activity graph use third-party hosted services. They can occasionally be slow, cached, rate-limited, or unavailable. The README text and local banner still work without them.
- GitHub profile statistics are community-maintained widgets, not official GitHub analytics. Treat them as visual extras rather than a measure of skill.
