# VIC 2026 — Week 01 webpage

This folder is ready to publish as a simple static GitHub Pages site.

## Folder structure

```text
.
├── index.html
├── .nojekyll
└── assets/
    └── week-01/
        ├── rosa-maria-leonardo.jpeg
        ├── mariana-chavana.jpeg
        ├── MAC-video.mp4
        └── MAC-video-poster.jpg
```

## Publish with GitHub Pages

1. Create a new GitHub repository, for example `vic-2026-week-01`.
2. Upload **all contents of this folder**, preserving the `assets/week-01/` structure.
3. Commit the files to the `main` branch.
4. Open **Settings → Pages** in the repository.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select `main` and `/(root)`, then save.
7. GitHub will publish the site at a URL of the form:
   `https://YOUR-USERNAME.github.io/vic-2026-week-01/`

## Updating the page

Edit `index.html` and/or replace files in `assets/week-01/`, commit the changes, and GitHub Pages will redeploy.

## Accessibility note

The supplied video has been web-optimised and a poster image has been added. Before public release, add captions (WebVTT) and ideally a text transcript if the spoken content is not already presented elsewhere on the page.

## Why this version does not use Quarto

The supplied page is already a bespoke bilingual HTML/CSS/JavaScript design. Publishing it directly with GitHub Pages preserves that design and avoids an unnecessary build step. Quarto becomes attractive if this grows into a multi-page or weekly-report site where you want to author content in Markdown, generate navigation automatically, manage citations, or reuse templates across many reports.
