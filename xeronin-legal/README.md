# xeronin-legal

A ready-to-publish GitHub Pages site containing the Terms of Service and Privacy Policy for:

- **Omniframe Bot**
- **Steward 13 Bot**

The operator name used throughout the site is **Xeronin**. No public email address, support invite, build system, JavaScript configuration, or database is required.

## Included pages

- `/` — Xeronin Legal home page
- `/terms/` — Terms of Service
- `/privacy/` — Privacy Policy

## Publish with GitHub Pages

### 1. Create the repository

Create a new GitHub repository named:

```text
xeronin-legal
```

A public repository is the simplest option for a public legal site.

### 2. Upload the files

Upload the **contents of this folder** to the repository. `index.html`, `README.md`, `terms`, `privacy`, and `assets` should be visible at the repository root.

You can also publish with Git:

```bash
git init
git add .
git commit -m "Publish Xeronin bot legal pages"
git branch -M main
git remote add origin https://github.com/YOUR-GITHUB-USERNAME/xeronin-legal.git
git push -u origin main
```

Replace `YOUR-GITHUB-USERNAME` with the GitHub account or organization that owns the repository.

### 3. Enable GitHub Pages

In the repository:

1. Open **Settings**.
2. Open **Pages** in the sidebar.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select the `main` branch.
5. Select the `/(root)` folder.
6. Save the setting.

After GitHub publishes the site, the URLs will normally be:

```text
https://YOUR-GITHUB-USERNAME.github.io/xeronin-legal/
https://YOUR-GITHUB-USERNAME.github.io/xeronin-legal/terms/
https://YOUR-GITHUB-USERNAME.github.io/xeronin-legal/privacy/
```

### 4. Add the links to both Discord applications

For **Omniframe Bot** and **Steward 13 Bot**, use:

```text
Terms of Service URL:
https://YOUR-GITHUB-USERNAME.github.io/xeronin-legal/terms/

Privacy Policy URL:
https://YOUR-GITHUB-USERNAME.github.io/xeronin-legal/privacy/
```

Paste those addresses into the Terms of Service URL and Privacy Policy URL fields in the Discord Developer Portal for each application.

## Updating the policies

The pages are plain HTML. Edit these files directly when needed:

```text
terms/index.html
privacy/index.html
```

Update the effective or “Last updated” date near the top of a policy after making a material change.

Review the Privacy Policy when either bot begins using a new category of data, stores message content, adds moderation records, adds paid features, uses an AI provider, adds analytics, or sends data to a new hosting or processing provider. The published policy must match what the bots actually do.

## Important legal note

This repository provides a practical general template, not legal advice. It cannot account for every bot feature, jurisdiction, business structure, or data practice. Xeronin remains responsible for keeping the published statements accurate and for obtaining professional legal advice where appropriate.

Discord requires applications seeking App Directory availability to have publicly available Terms and Privacy pages, and its Developer Terms require an application privacy policy to accurately describe collection, use, sharing, and deletion requests. Relevant official references:

- [Discord Developer Terms of Service](https://support-dev.discord.com/hc/en-us/articles/8562894815383-Discord-Developer-Terms-of-Service)
- [Discord Developer Policy](https://support-dev.discord.com/hc/en-us/articles/8563934450327-Discord-Developer-Policy)
- [Discord App Content Requirements](https://support-dev.discord.com/hc/en-us/articles/9489299950487-App-Directory-App-Content-Requirements-Policy)
- [GitHub Pages publishing source](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

## License

The website code and template text are provided under the MIT License. See `LICENSE`.
