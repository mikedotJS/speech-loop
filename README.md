## Speech Loop

Ultra-minimal browser app for looping through a list of sentences using the Web Speech API. Built with React via CDN—no build tooling required.

### Local Preview

```bash
open index.html
```

Any modern browser (Chrome, Edge, Safari, Firefox Nightly) with Speech Synthesis enabled will work.

### Deploying to GitHub Pages

1. Create a new GitHub repository (e.g. `speech-loop`), then copy the contents of this directory into it.
2. Commit `index.html` and `README.md`, push to GitHub’s `main` (or `master`) branch.
3. In the repository settings, open **Pages** and set:
   - Source: `Deploy from a branch`
   - Branch: `main` (or your default) / folder: `/ (root)`
4. Save. Within a minute or two GitHub Pages will publish the site at `https://<your-username>.github.io/<repo-name>/`.

Optional enhancements:

- Add a `CNAME` file if you plan to use a custom domain.
- Place assets (icons, manifest, etc.) alongside `index.html`—Pages serves the repository root as-is.
