# Yanping Zhu — personal website

Single-page academic site served by GitHub Pages. The whole site is `index.html` (content and styles), plus `images/headshot.jpg`.

## Editing

Open `index.html` on GitHub, click the pencil icon, edit, and commit. The live site updates within a minute or two.

- **Add a paper:** copy one `<article class="paper">…</article>` block and change the title, links, coauthors, and abstract. Give the abstract a new `id` (for example `abs-newpaper`) and set the Abstract button's `aria-controls` to the same value.
- **Update a paper PDF:** upload the new version to the `papers` folder with the same file name (for example `papers/zhu_cecl.pdf`), so existing links keep working.
- **Add media coverage:** copy the `<p class="paper-media">…</p>` line inside a paper and change the outlet name and link.
- **Add a list (e.g. Publications):** add `<h3 class="list-title">Publications</h3>` above the Working Papers heading, followed by its paper blocks.
- **Add a course:** copy the `<li>…</li>` block inside `<ul class="course-list">` and change the course name and the line below it (year, term, or role).
- **Add a CV:** upload `cv.pdf` to the repository root, then remove the `<!--` and `-->` around the three commented-out CV links in `index.html` (navigation bar, intro, contact section).
- **Change the photo:** replace `images/headshot.jpg` with a square image (about 800×800).
- **Change the colors:** the accent is NYU Violet (`--accent: #57068c`, with `--accent-dark` for hover and `--tint`/`--panel` for the light violet backgrounds), set at the top of the `<style>` block.
