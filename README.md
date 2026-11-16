# MusicMate site

Static pages for [musicmatehq.com](https://musicmatehq.com), published with GitHub Pages.

## Add a release on the Updates page

The public page is [https://musicmatehq.com/updates/](https://musicmatehq.com/updates/). Edit `updates/index.html`. Releases live in `<section id="latest">`, newest first. Each release is one `<article class="release">`.

1. Copy the first `<article class="release">` block.
2. Paste the copy above the other articles.
3. Update that copy:
   - `<h3>` is the version, for example `Version 1.1.0`.
   - `<p class="release-date">` is the date. Write the public date, such as `December 2, 2026`. Keep the text `Launching soon` when a date should not be published yet.
   - Replace the lead sentence and put one change in each `<li>`.
4. Leave `<section id="coming">` as a single note. Do not add a date there, and do not name a specific future feature.

Skeleton:

```html
<article class="release">
  <h3>Version 1.1.0</h3>
  <p class="release-date">Month D, YYYY</p>
  <p>Short summary of this release.</p>
  <ul>
    <li>One change per item</li>
  </ul>
</article>
```

Do not edit `privacy.html` or `terms.html` when you add a release. The same steps are in a comment above the Latest section in `updates/index.html`.
