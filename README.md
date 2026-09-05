# The Human Mind: Landing Page

Live site: https://ashwikbire.github.io/My-Portfolio/the-human-mind-landing-page.html

This is the landing page for **The Human Mind: A Data Scientist's Guide to Psychology**, a memoir by Ashwik Bire about surviving a posterior circulation stroke at twenty-four and the recovery that followed.

## What's here

A single self-contained HTML file, `the-human-mind-landing-page.html`. No build step, no dependencies, no framework. The author photo is embedded directly in the file as base64, so the page works standalone if you ever move it somewhere other than GitHub Pages.

## Where to read or buy the book

- **Read free:** linked from the "Read the eBook" button on the page
- **Kindle:** update the link once the Amazon listing is approved and live
- **Paperback:** update the link once the KDP paperback listing is approved and live

Both Amazon links currently point to placeholders or are missing entirely, search this file for `TODO` comments once the listings go live, or just replace the button `href` values directly.

## How to update this page

1. Edit `the-human-mind-landing-page.html` directly, all styling is in a `<style>` block at the top, all content is plain HTML further down.
2. Commit and push to the `main` branch.
3. GitHub Pages redeploys automatically, changes are usually live within a minute or two.

Common edits:
- **Swap the free-read link for Amazon links** once you decide the book should be paid-only. Search for `drive.google.com` in the file, there are two buttons that use it.
- **Update the stats band** (9 days in ICU, 24 years old, 15 chapters, 2025) if you ever revise the book.
- **Add a new testimonial or review** by copying the existing `<blockquote>` block in the "Why this book exists" section.

## Design system

- Colors: navy (`#1B2A6B`), gold (`#C9A84C`), off-white background (`#F4F6FB`), matching the book's interior design.
- Fonts: Georgia for headings, system sans-serif for body text.
- Layout: flexbox throughout (not CSS grid), for compatibility across older rendering engines.

## Author

Ashwik Bire, data scientist and author, based in Pune, India.

- LinkedIn: https://linkedin.com/in/ashwik-bire-b2a000186
- Portfolio: https://ashwikbire.github.io/My-Portfolio/

## License

All book content, cover design, and photos are copyright Ashwik Bire. This repository is for hosting the promotional landing page only, it is not a license to redistribute the book itself.
