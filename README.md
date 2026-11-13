# letters from kate

A self-contained static copy of the 21 published letters and About page from https://lettersfromkate2.wordpress.com/, retrieved 13 November 2026. Original text, paragraph/line breaks, dates and artwork credits are preserved. Images and Newsreader fonts are stored locally. The dark design is adapted for a responsive archive and reading pages.

## Publish on GitHub Pages

1. Put the contents of this folder at the root of `mol-sarg/lettersfromkate.github.io` on the `main` branch. `index.html`, `assets/`, `about/`, and the year folders must be directly in the repository, not inside another folder. Include `.nojekyll`.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select **main** and **/(root)**, then **Save**.
5. Wait for the Pages deployment to finish. Use the URL GitHub displays there.

With the current repository name and no custom domain, the expected URL is https://mol-sarg.github.io/lettersfromkate.github.io/ . The repository name does not make the site live at lettersfromkate.github.io.

Official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Editing

No installation or build is required. Each letter is an `index.html` inside its original year/month/day/title folder. Edit the content within `<div class="prose">` to change a letter. `<p>` marks a stanza/paragraph; `<br>` marks a line break. The homepage list is in the root `index.html`; design is in `assets/style.css`. To add a letter, duplicate an existing letter folder, update its heading/date/content, add an entry on the homepage, and update the neighbouring letter links.

Open `index.html` locally to preview. All links are relative, so they work under the repository's Pages subdirectory as well.

## Migration boundaries

This is a snapshot, not automatic sync with WordPress. Comments, WordPress likes, email subscriptions, and private/draft posts are not migrated. The poem drafted in chat has not been added. The original WordPress site has not been changed. Existing WordPress URLs do not automatically redirect to GitHub Pages. Retain original artwork credits and applicable image rights. Newsreader is distributed under the SIL Open Font License; see assets/OFL.txt.
