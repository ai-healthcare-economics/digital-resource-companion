# Canonical Source Policy

The repository keeps one authoritative source for each substantive resource family.

- `chapters/` is the canonical location for core institutional records, reference guides, analytical modules, supplemental specialist resources, and chapter process maps.
- `worked_examples/` is the canonical location for complete worked cases and the common case-analysis method.
- `process/` is the canonical location for the Master Institutional Decision Lifecycle, decision-stage records, and dependency maps.
- `publications/` contains the definitive reading editions of the Digital Resource Companion.
- `bundles/` contains consolidated convenience editions generated from the core resources.
- `catalogs/` contains synchronized indexes and relationship data.
- `docs/` contains the GitHub Pages presentation layer. It may contain web-optimized copies of diagrams and data required for the static website, but it is not a second authoritative source.
- The Python analytical modules retain selected helper files within each module so that a module can be downloaded and run independently. This repetition is intentional; module identifiers and version metadata remain the control points.

When a resource is revised, update its canonical source first and then regenerate or synchronize the corresponding catalog, website page, bundle, and publication entry. Stable resource identifiers should be preserved unless a documented replacement is required.
