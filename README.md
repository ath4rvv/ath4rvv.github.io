# ath4rv — personal site

Plain static site: `index.html` + favicons. No build step.

**Deploy (GitHub Pages):** push these files to the repo root, then Settings → Pages → Deploy from branch → `main` / root.

**Writes page:** the `writes` link in the footer row opens `#writes` (list) and `#writes/<slug>` (article) inside the same `index.html`.
To add a post, add an object `{ slug, title, date: "YYYY-MM-DD", body: "<p>…</p>" }` to the `ART` array at the end of the last `<script>`.

