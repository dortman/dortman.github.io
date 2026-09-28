# Vantage Consulting Group

Static corporate website for Vantage Consulting Group, Inc., hosted on GitHub
Pages at https://vantagecg.com/. No build step or production JavaScript dependencies.

## Local preview

From the repository root:

```sh
python3 -m http.server 8080 --bind 127.0.0.1
```

Open http://127.0.0.1:8080.

## Editing

- `index.html`: company copy, projects, contact information, and search metadata.
- `assets/css/site.css`: layout, typography, colors, responsive and print styles.
- `assets/js/site.js`: accessible mobile navigation and copyright year.
- `assets/fonts/`: self-hosted DM Sans and its SIL Open Font License.
- `welcome.html`: redirects the old duplicate page to the homepage.
- `CNAME`, `robots.txt`, `sitemap.xml`: domain and indexing configuration.

The redesign uses original markup and styling, an inline architectural SVG, and
native disclosure elements for project details. Content and navigation remain
available without JavaScript. Fonts are hosted locally; the page makes no
third-party requests. Legacy template assets remain in the repository but are
not loaded by the redesigned site.

## Content notes

Company facts and project descriptions were supplied by Dave Ortman. Vantage
was founded in 2005; Dave's personal public-sector experience predates the firm.
CalPERS and DOJ were direct engagements; Caltrans was through a prime contractor.
QuickMap copy describes the initial implementation and subsequent handoff to
Caltrans, not responsibility for the current site's behavior. No project
screenshots or agency logos are used.

The approximate 150 million document count, production status, low maintenance
and ownership costs, and CMAS agreement number were supplied by the owner.
The owner also supplied a California DGS certification profile identifying:

- Legal name: VANTAGE CONSULTING GROUP, INC.
- Certification: SB(Micro), ID 44449.
- Certification period: March 13, 2025 through March 31, 2027.
- CMAS agreement supplied separately: 3-25-01-1036.

Review the certification information before March 31, 2027. Keep project and
contracting information current as the business changes. No numerical cost
savings or accessibility certification is claimed.

## Review before publishing changes

Check desktop and mobile layouts, keyboard navigation (including Escape to close
the mobile menu), project disclosures, email/phone links, reduced-motion behavior,
and the legacy-page redirect. Verify no horizontal overflow at 320px and at zoom.
Publishing depends on the repository's GitHub Pages configuration.
