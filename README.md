# Customer App External

OnePort 365 customer mobile app prototype: home, quote review (accept / reject with reason), shipment tracking with document upload, and account profile.

Two prototypes, each a single static HTML file (no build step):

- **Mobile app** — `index.html` (served at `/`)
- **Web portal** — `web/index.html` (served at `/web/`): desktop layout with sidebar navigation, tables, detail pages and dialogs; same data and flows as the mobile app.

## Deploy on Vercel
Import this repository in Vercel, set **Framework Preset** to **Other**, leave the build command empty and deploy.
