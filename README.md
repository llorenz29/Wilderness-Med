# Georgetown Wilderness Medicine

Website for the Georgetown University School of Medicine Wilderness Medicine Group.

It is a static site with no build step: `index.html` plus `logo.png`, served by GitHub Pages from the `main` branch.

## Updating the site

Everything that changes semester to semester lives in the `EDIT HERE` block near the bottom of `index.html`:

- `events`: one entry per event (`date` as `YYYY-MM-DD`, `title`, `where`, `kind`, `blurb`, optional `link`). Past events hide themselves, and the first upcoming one shows as "Next up" in the header.
- `sampleEvents`: set to `false` once the events are real, to hide the "sample schedule" note.
- `board`: student leaders, e.g. `{ name: "First Last", role: "President, M2" }`. The Student board section appears once this has entries.
- `faculty`, `skills`, `email` and `links` (add the group's Instagram handle under `links.instagram`).

Edit the file on GitHub, commit, and the live site updates within a minute or two.
