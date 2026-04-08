# Research Papers

Academic papers by **Ezra Mulaga**, hosted via GitHub Pages.

## Live Site

[https://ezramulaga.github.io/Research-Papers/](https://ezramulaga.github.io/Research-Papers/)

## Repository Structure

```
Research-Papers/
├── docs/                    # GitHub Pages root
│   ├── index.html           # Landing page
│   ├── robots.txt           # Crawler permissions
│   ├── sitemap.xml          # Search engine sitemap
│   ├── assets/
│   │   └── styles.css
│   └── papers/
│       ├── paper-one/
│       │   ├── index.html
│       │   ├── paper.pdf
│       │   └── citation.bib
│       ├── paper-two/
│       │   ├── index.html
│       │   ├── paper.pdf
│       │   └── citation.bib
│       └── paper-three/
│           ├── index.html
│           ├── paper.pdf
│           └── citation.bib
├── Papers/                  # Source / working copies
│   └── LICENSE
├── LICENSE
└── README.md
```

## GitHub Pages Setup

1. Go to **Settings → Pages**
2. Set **Source** to `Deploy from a branch`
3. Set **Branch** to `main` and folder to `/docs`
4. Save — the site will be live at the URL above.

## Google Scholar Indexing

Each paper's `index.html` includes `<meta name="citation_*">` tags recognised by Google Scholar.

## License

[MIT](LICENSE) © 2026 Ezra Mulaga
