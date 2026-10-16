# Muhammed Haja: Cybersecurity Portfolio

A static personal portfolio built with plain HTML, CSS and vanilla JavaScript.
No frameworks, build tools, backend, trackers or external requests.

## Files
- `index.html`: page content
- `style.css`: styling (colors and spacing are CSS variables at the top)
- `script.js`: mobile menu, reveal-on-scroll, active nav link, back-to-top
- `assets/README.md`: notes on optional assets and the resume PDF

## Run locally
Open `index.html` in a browser. No server is needed.

## Add your resume
1. Name your file exactly `resume.pdf` and put it in the repository root (next to `index.html`).
2. In `index.html`, find the comment `RESUME BUTTON` and replace the disabled
   `<button>` with:
   ```html
   <a class="btn btn--resume" href="resume.pdf" download>Download Resume</a>
   ```
3. Remove the "Resume not yet available" note next to it.
4. Commit and push, wait for GitHub Pages to rebuild, then click the button on the live site to confirm it downloads.

## Add a project
Copy the `<article class="card project reveal">` block in the Projects section.
Update the title, status (`status--planned`, `status--progress` or `status--complete`)
and description. Only use `status--complete` for finished work. Replace
"Repository coming soon" with a real GitHub link only once the repository exists.

## Contact
The contact section uses a `mailto:` link. A working contact form would need a
form provider or a backend, which this static site intentionally avoids.

## Deploy on GitHub Pages
Repository **Settings → Pages → Build and deployment → Source: Deploy from a branch →
Branch: `main`, folder: `/ (root)` → Save**. (GitHub's interface may vary slightly.)

- Repository named `hajamuha1234.github.io` → `https://hajamuha1234.github.io/`
- Any other repository name → `https://hajamuha1234.github.io/<repository-name>/`
