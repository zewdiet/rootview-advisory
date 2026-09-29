# Rootview Advisory — Updated Multi-page Website

This package **replaces** the older `rootview-advisory-main` website with the latest approved Rootview design and content. It is a static website, with no backend, build system, or paid JavaScript framework.

## Structure

- `index.html` — homepage.
- `about.html`, `team.html`, `contact.html`, `location.html` — Home subsections.
- `services.html` — overview with six independently linked services.
- `data.html`, `analytics.html`, `research.html`, `bds.html`, `meal.html`, `training.html` — dedicated service pages, each with **six clickable capability cards** and modal analytical illustrations.
- `projects.html` — project portfolio placeholder, pending verified content.
- `vacancies.html`, `consultants.html`, `enumerators.html` — vacancies and roster pages.
- `publications.html`, `blogs.html`, `reports.html` — knowledge publications.
- `styles.css`, `script.js` — shared responsive design and interactions.
- `assets/` — cropped approved Rootview logo, the Zemen headshot, and an **illustrative/non-authentic** portrait placeholder for Tibebu.
- `sectors.html` and `approach.html` — compatibility redirects from older versions.

## Review locally

Extract the zip and open `index.html`, or preview with a local server:

```sh
python -m http.server 8000
```

Then visit `http://localhost:8000/`. Every page can be opened directly. No npm install is required. Google-hosted webfonts are optional; system fonts are used when offline.

## Deploy

1. **Keep a backup** of the previous repository first.
2. In the `rootview-advisory` repository, remove the obsolete files and add the **contents of this extracted directory** to the repository root (not a nested folder and not the zip itself).
3. Commit the changes. Confirm that `index.html`, `styles.css`, `script.js`, and `assets/` are at the root.
4. Publish using your configured static host. The site uses relative paths, so it works at a domain root or a GitHub Pages project subpath.
5. Test navigation, capability dialogs, and mobile layout before sharing the site publicly.

## Publication checks

- Confirm the official firm address, phone, email and location before replacing explicit placeholders.
- Confirm team names, responsibilities, biographies, and permissions. **The portrait shown for Tibebu Aragie is illustrative and not his verified likeness.** Replace it with an authorized photograph before publication.
- Do not imply that sample charts or diagrams show actual Rootview project findings; they are conceptual illustrations.
- Confirm current vacancies, commissioned projects, and report/publication permissions before advertising them as actual work.
- Confirm availability and legal permissions for each advertised service.
- Do not upload respondent-level data or confidential client material to this public repository.

Content is preserved from the latest approved interactive preview. Main changes from the earlier repo: the new 19-page information architecture; enlarged accessible typography; revised blue/green/white style; approved logo in the header and footer, not the homepage hero; new service capability interactions and diagrams; project/vacancy/publication pages; updated Team cards; independent files for easier maintenance.
