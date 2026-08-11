# GitHub Pages Web Companion

The `docs/` directory is the publication source for the browser-based Digital Resource Companion.

## What is included

- responsive landing page aligned with the current five-Part, fifteen-chapter book structure;
- chapter navigation pages;
- searchable master resource catalog;
- browser demonstrations for all 16 current worked cases;
- a browser implementation of **AIHE-EX05 — Local Validation Report Template**;
- links back to canonical Word, spreadsheet, LaTeX, data, and computational resources in the repository.

## Enable GitHub Pages

In the repository on GitHub:

1. Open **Settings** → **Pages**.
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Select the `main` branch and the `/docs` folder.
4. Save the setting.

For the current organization and repository name, the expected site address is:

`https://ai-healthcare-economy.github.io/ai-healthcare-economics-companion/`

## Design principle

The web layer is deliberately thin. It improves discovery and permits safe exploration of synthetic examples, but it does not create a second independent source of truth. Canonical editable records remain in the chapter folders. When a browser page and a canonical resource differ, the current canonical repository resource and the current book take precedence.

## Data handling

The demonstrations run entirely in the browser and do not contain analytics or external form services. Do not enter identifiable patient information, credentials, confidential contracts, or other controlled institutional information. Use synthetic data for public demonstrations and governed local copies for operational work.

## Maintenance

When a worked case changes, regenerate or manually update the corresponding page under `docs/demos/`. The resource browser is driven by `docs/assets/catalog.js`, which should be regenerated from `catalogs/MASTER_RESOURCE_CATALOG.json` whenever the catalog changes.


## Release V1.0 navigation layers

The web companion now supports four complementary routes:

1. **By chapter** — the scholarly organization of the book.
2. **By decision stage** — the ten-stage institutional decision lifecycle.
3. **By process flow** — master, chapter, and resource-level process maps.
4. **By editable form** — browser drafting for the 24 core resources and seven reference guides.

Browser forms keep reference and guidance cells fixed while allowing local response cells to be edited. They can export JSON and CSV but should not be used for identifiable patient data or confidential institutional material on a public site.

Process pages are generated from the canonical repository flows. Resource-level step records are maintained in both CSV and JSON for reuse by web interfaces and software integrations.


## Additional V1.0 pages

- `python-analytics.html` provides a filterable catalog of the 39 computational modules.
- `bundles.html` explains the consolidated offline forms and workbook editions.
- JSON catalog files and resource schemas are generated from the canonical repository records.
