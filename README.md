# Hadi Susanto Academic Page

Static single-page academic website built from the previous Hadi Susanto website,
with a searchable publication list, teaching history, group members, and contact links.

## Files

- `index.html` contains the page structure and section copy.
- `styles.css` contains the responsive layout and visual design.
- `script.js` contains the imported `publications` array and filtering behavior.
- `assets/academic-hero.png` is the generated hero image.
- `papers/` contains the publication and thesis PDFs copied from the old website.

## Notes

- The imported publication list contains 188 records: 157 articles, 30 chapters/proceedings, and 1 thesis.
- All 201 local paper/thesis PDF links currently referenced by the site were found and copied into this project.
- The missing legacy PDF `papers/yusupov2018.pdf` was omitted from its publication entry so the new page does not show a broken PDF button.
- The About section links to `resume.pdf` for the full Resume/CV. Place that file beside `index.html` before publishing if it is not already present.
- Open `index.html` in a browser. No build step is required.
