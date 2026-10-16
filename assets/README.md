# Assets

The site currently needs no extra assets. The favicon is an inline SVG inside `index.html`.

## Resume PDF
Keep `resume.pdf` in the repository root, not in this folder, so the link is simply
`href="resume.pdf"`. If you prefer to keep it here, save it as `assets/resume.pdf` and use
`href="assets/resume.pdf"`. Always use relative paths with no leading `/`, so the site
works from a repository subpath.

## Optional images
If you add images later, put them in this folder, reference them as `assets/filename.png`,
and give meaningful images descriptive `alt` text (use `alt=""` for decorative ones).
Do not add screenshots or logos that don't represent real work or real affiliations.
