# Atikul Gazi — professional portfolio

Personal website covering iOS engineering, SmartThings, SCClient SDK interoperability, camera streaming, technical leadership and on-device AI exploration. Built with Jekyll and the cvless theme.

Live site: https://atiksplanet.github.io/

## Content

- `index.md`: introduction, selected projects and contact links.
- `cv.md`: professional experience, role progression, skills and education.
- `_config.yml`: profile details, metadata and social links.
- `assets/files/Atikul_Gazi_Professional_Resume.pdf`: professional résumé download.

## Publishing

GitHub Pages uses **GitHub Actions**, with `.github/workflows/pages.yml` building and deploying pushes to `codex/update-professional-portfolio`. This is the explicitly selected publishing branch; `main` is not the site source. The workflow installs the project's Bundler dependencies, builds with Jekyll, verifies essential outputs and uploads the generated `_site` artifact before deployment.

In repository Settings → Pages, keep the source set to GitHub Actions. Deployment uses the `github-pages` environment. If branch restrictions are enabled for that environment, the publishing branch must be permitted; keep any required approval rules in place.

With compatible Ruby and Bundler dependencies installed, use `bundle install`, then `bundle exec jekyll serve` for preview or `bundle exec jekyll build` for validation.

Keep claims factual. Distinguish SmartThings app experience from more recent SCClient work; label AI experimentation as proof-of-concept work. Do not publish proprietary source code or internal repository links.
