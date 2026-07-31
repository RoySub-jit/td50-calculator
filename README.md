# TD50 Calculator

Standalone browser-based TD50 calculation aid for article-derived rodent tumor-incidence data.

## How to use

Open `index.html` in a browser, enter study-level details, dose/incidence rows, and click **Calculate**. The app runs locally in the browser and does not make network calls.

## Scope

This tool provides a transparent CPDB-style estimate using user-entered incidence data, experiment-duration `f^2` correction, a linearized one-hit slope fit, an audit table, plots, bootstrap resampling, CSV export, study JSON export/import, and browser print/PDF export.

It is intended for education, calculation audit, and method review. It is not an official CPDB, regulatory, or externally validated TD50 calculation engine.

## Privacy

The app is a static HTML file. It has no external dependencies and no remote data transfer.
