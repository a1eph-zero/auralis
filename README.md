# Federation of Auralis Website

Official website for the **Federation of Auralis**, an English-speaking virtual nation built around democracy, law, government, community, and civic participation.

## Overview

This repository contains the public-facing website of Auralis.

The website is designed as a lightweight static site using:

- HTML
- CSS
- JavaScript

No framework, build process, database, or server is required.

## Current Sections

- Home
- About Auralis
- Core Values
- Federal Government
- Constitution
- Citizenship
- Discord Join Links

## Project Structure

```text
auralis-website/
├── index.html
├── README.md
├── css/
│   └── style.css
├── js/
│   └── main.js
└── assets/
```

## Before Publishing

Open `index.html` and replace every placeholder Discord link:

```text
https://discord.gg/REPLACE-ME
```

with the official Auralis Discord invite link.

Also replace the Constitution placeholder:

```html
href="#"
```

with the real Constitution page, PDF, document, or Discord channel link.

## Local Preview

You can preview the website by opening:

```text
index.html
```

in a web browser.

For easier development, open the project in Visual Studio Code and use the **Live Server** extension.

## Deployment

This website can be deployed for free using any static hosting provider.

Recommended options:

- GitHub Pages
- Cloudflare Pages
- Netlify
- Vercel

### GitHub Pages

1. Upload the files to a GitHub repository.
2. Open the repository settings.
3. Go to **Pages**.
4. Select **Deploy from a branch**.
5. Choose the `main` branch and the root directory.
6. Save the settings.

The website will then be published at an address similar to:

```text
https://YOUR-USERNAME.github.io/auralis-website/
```

## Public Repository Policy

This repository is intended to be public.

Safe to publish:

- Website source code
- Public government information
- Constitution links
- Public branding assets
- Documentation

Do not publish:

- Discord bot tokens
- API keys
- Private credentials
- Environment files containing secrets
- Database passwords
- Private keys

Recommended `.gitignore` entries:

```gitignore
.env
.env.*
*.pem
*.key
.DS_Store
```

## Branding

The names **Federation of Auralis**, **Auralis**, and **AUR**, along with any official flag, seal, emblem, or other original brand assets, belong to the Auralis project.

Publishing the website source code does not automatically grant permission to impersonate the Federation of Auralis or present another project as an official Auralis service.

## Contributing

Suggestions, bug reports, accessibility improvements, and design improvements may be submitted through GitHub Issues or Pull Requests.

Major changes should be discussed before submission.

## License

The source code may be released under the MIT License if the project owner chooses to add a `LICENSE` file.

Brand names, logos, seals, flags, constitutional documents, and other identity assets may be subject to separate usage restrictions.

Until a license is added, the repository should not be assumed to be open source.

## Status

This website is an early public version and may be expanded with:

- Government directory
- Election results
- News and announcements
- Public laws and records
- Officeholder profiles
- Citizen services
- Multilingual support

---

**Build more than a community. Build a nation.**
