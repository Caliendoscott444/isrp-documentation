# Iowa State Roleplay Documentation

A free, GitHub Pages-hosted documentation website built with MkDocs Material.

## Included

- Home page and navigation
- Community Handbook
- Punishment Guide
- Training Guide
- Search
- Dark/light theme toggle
- Responsive mobile layout
- Automatic GitHub Pages deployment with GitHub Actions

## Publish for free

1. Create a public repository on GitHub named `isrp-documentation`.
2. Upload the contents of this folder to the repository's `main` branch. The `.github` folder must be included.
3. Open **Settings → Pages** in the repository.
4. Under **Build and deployment**, select **GitHub Actions** as the source.
5. Edit `mkdocs.yml` and replace `YOUR-GITHUB-USERNAME` in `site_url`, `repo_name`, and `repo_url`.
6. Push the changes. Open the **Actions** tab and wait for “Deploy ISRP Documentation” to finish.
7. Your website will be available at:
   `https://YOUR-GITHUB-USERNAME.github.io/isrp-documentation/`

GitHub Pages is free for public repositories. No paid hosting or custom domain is required.

## Preview locally (optional)

Install Python, then run:

```bash
pip install -r requirements.txt
mkdocs serve
```

Open the local address printed by MkDocs.

## Important content note

The original Jackson County GitBook pages were not available to this build. The three ISRP guides are therefore newly drafted starter content and are not claimed to be exact reproductions. Before launch, ISRP management should verify the policies and fill in the explicitly marked items requiring official decisions.

## Branding

The configuration is set up for an ISRP logo and favicon. Add your approved image files as:

- `docs/assets/isrp-logo.png`
- `docs/assets/favicon.png`

If those files are not added, remove the `logo` and `favicon` lines from `mkdocs.yml`.
