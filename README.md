# Financial Analytics Portfolio — Labiba Bushra Zeba

A single self-contained `index.html` file showcasing three FIN 4333 Financial Analytics projects (Team Hemisphere): dataset engineering for Grameenphone (DSE: GP), GARCH volatility modeling for Target Corp (TGT), and an ARIMA vs. LSTM return-forecasting comparison.

All charts are embedded directly in the HTML (base64), so this is a **single file with no external dependencies** other than two Google Fonts links — perfect for GitHub Pages.

## How to publish on GitHub Pages

1. Create a new GitHub repository. For a personal site at `https://yourusername.github.io`, name it exactly `yourusername.github.io`. For a project page instead, any repo name works.
2. Upload `index.html` to the **root** of the repository (drag-and-drop on github.com works fine, or `git add`, `git commit`, `git push`).
3. Go to the repository's **Settings → Pages**.
4. Under "Build and deployment," set **Source** to "Deploy from a branch," choose the `main` branch and `/ (root)` folder, then **Save**.
5. Wait 1–2 minutes, then visit the URL GitHub gives you (e.g. `https://yourusername.github.io` or `https://yourusername.github.io/repo-name`).

## Before you publish — two things to double-check

- **LinkedIn link**: already set to `https://www.linkedin.com/in/labiba-bushra-zeba-63b9a0389/` — confirm this is your current public profile URL.
- **Email**: already set to `labibabushra18@gmail.com` in the Contact section and as a `mailto:` link.

## Editing later

Open `index.html` in any text editor. Section landmarks to search for:
- `id="about"` — bio and skills
- `id="project-1"`, `id="project-2"`, `id="project-3"` — each project card
- `id="ai"` — AI disclosure section
- `id="contact"` — email / LinkedIn

Colors and fonts are controlled by CSS variables at the top of the `<style>` block (`:root { ... }`), so a palette or font change only needs to happen in one place.
