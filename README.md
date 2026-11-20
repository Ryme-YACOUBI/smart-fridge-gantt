# Smart Fridge Gantt — GitHub Pages

This folder contains a standalone visual Gantt chart generated from the TeamGantt CSV export.

## Publish with GitHub Pages
1. Create a GitHub repository (for example `smart-fridge-gantt`).
2. Upload `index.html` and `project-plan.csv` to the repository root.
3. Open **Settings → Pages**.
4. Under Build and deployment, select **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then Save.
6. Wait for GitHub Pages to publish and open the URL shown in Settings → Pages.

The page displays the project timeline directly, without TeamGantt menus. It is a static copy: edits in TeamGantt do not sync automatically. The CSV does not contain dependency or resource-assignment columns, so those are not displayed.
