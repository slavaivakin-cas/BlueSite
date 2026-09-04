# BlueSite — UI prototypes

Three front-end versions of a BlueSite / PSVPortal-like screen:

- The repository root contains the original non-interactive recreation.
- `/1/` contains the interactive Unit-Floor management prototype.
- `/2/` contains the original layout with expandable waterfall Unit-Floor tables.

It is a front-end demonstration only: no request is sent to ad networks, mediation, or 1C. Changes live in browser memory and reset after a page reload.

## Interactive version

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
4. The original version will be published at `https://slavaivakin-cas.github.io/BlueSite/`.
5. The interactive version will be published at `https://slavaivakin-cas.github.io/BlueSite/1/`.
6. The expandable-table version will be published at `https://slavaivakin-cas.github.io/BlueSite/2/`.

All visible app, account, e-mail, and AdMob identifiers in this published version are demo values.
