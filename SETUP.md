# GitHub profile README — setup guide

This profile kit is for `github.com/deatharoundthecorner`.

## Files in this kit

```text
README.md
SETUP.md
assets/
  cyber-banner.png
.github/
  workflows/
    snake.yml
```

## Upload using the GitHub website

1. Extract the ZIP file on your computer.
2. Open <https://github.com/deatharoundthecorner/deatharoundthecorner>.
3. Select **Add file → Upload files**.
4. Upload `README.md`, `SETUP.md`, the `assets` folder, and the `.github` folder from the extracted kit.
5. Keep the folder paths unchanged. In particular, the workflow must be at `.github/workflows/snake.yml`.
6. Scroll down, enter a commit message such as `Refresh profile README`, and select **Commit changes**.

If GitHub's browser uploader does not preserve a hidden `.github` folder when you drag it in, create the folders in the repository using **Add file → Create new file** and enter `.github/workflows/snake.yml` as the filename. Paste the contents from the matching file in this kit.

## Activate the contribution snake

1. Open the profile repository's **Settings → Actions → General**.
2. Under **Workflow permissions**, select **Read and write permissions** and save if required.
3. Open the **Actions** tab.
4. Choose **Generate contribution snake** from the workflow list.
5. Select **Run workflow** and run it on the default branch.
6. Wait for the run to finish successfully. It creates or updates the `output` branch with the SVG images.

The snake image will be blank or broken until the first successful run creates those files. The workflow also runs once per day automatically.

## Why the stats cards were removed

The old README used third-party GitHub statistics and activity-graph image services. Those services can be unavailable, rate-limited, or return empty images. This version avoids those fragile score cards and instead highlights three real repositories, their engineering focus, and GitHub's own contribution calendar, which already appears below the profile README on the profile page.

## Before publishing

- Confirm that the email and LinkedIn links are the contact details you want to make public.
- Remove or edit any technology you do not use or are not actively learning.
- Pin your strongest repositories on your GitHub profile so visitors can find the projects quickly.
