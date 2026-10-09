# Atikul Gazi — professional portfolio

Responsive, buildless portfolio for iOS, SDK and IoT engineering, with on-device AI proof-of-concept work. Built with HTML, CSS and JavaScript.

## Local preview

Run `python3 -m http.server 8765 --bind 127.0.0.1` in this folder and open http://127.0.0.1:8765/. Stop the server with Ctrl+C.

## Files

- `index.html`: portfolio content and layout.
- `styles.css`: responsive styles and print layout.
- `app.js`: project filters, detail dialogs, navigation and email copying.
- `assets/`: portrait, favicon and professional résumé.

## GitHub Pages

The workflow in `.github/workflows/pages.yml` validates pull requests targeting `main` without deploying them. After approval and merge, pushes to `main` publish the portfolio at https://atiksplanet.github.io/. Keep Settings → Pages → Source set to GitHub Actions. The `github-pages` environment must allow `main`.

Only `index.html`, `styles.css`, `app.js` and `assets/` enter the deployment artifact. Private content notes, contribution wikis and immigration documents are intentionally excluded.

Before merging this migration, disable the older **Build and deploy portfolio** workflow that publishes from `codex/update-professional-portfolio` to avoid two branches updating the same website. Do not delete its branch; it retains the earlier Jekyll site for reference.

## Content boundaries

Keep SmartThings app work distinct from more recent SCClient/IoTivity contributions. AI work is exploratory, not a production deployment claim. Project illustrations are not actual app screenshots. The model repository is a learning fork. Do not add private employer repository links or proprietary code.
