# BlueSite — interactive UI prototype

Static prototype of a BlueSite / PSVPortal-like screen for managing waterfall Unit-Floors.

It is a front-end demonstration only: no request is sent to ad networks, mediation, or 1C. Changes live in browser memory and reset after a page reload.

## What the prototype demonstrates

- Adding, editing, deleting, and undoing a waterfall Unit-Floor.
- Duplicate-price validation inside each format.
- A pending-change review before `UPDATE NETWORKS`.
- Separate compact statuses for `NET`, `MED`, and `1С`.
- Detail tooltips on status hover/focus.
- The explicit `1С` deletion limitation after a simulated update.

## Publish with GitHub Pages

The repository root contains `index.html`, so GitHub Pages can publish it without a build step:

1. Open **Settings → Pages** in the GitHub repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Choose branch `main` and folder `/(root)`, then save.
4. The site will be published at `https://slavaivakin-cas.github.io/BlueSite/`.

All visible app, account, e-mail, and AdMob identifiers in this published version are demo values.
