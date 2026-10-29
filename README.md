# 2ndScan website

The website for [2ndScan](https://2ndscan.com), a free, independent thinking habit for every age: take a second look.

The site is plain HTML and CSS, with no scripts, cookies or tracking. It's hosted free on GitHub Pages from the `main` branch.

## Pages

- `index.html`, the home page. It keeps to one simple message:
  1. Hero: "Take a second look."
  2. How it works: the three questions and the one rule
  3. One skill, three disguises: three invented examples, switched with buttons that work without scripts
  4. Why a habit, not another app?, with a link to the evidence page
  5. Our pledge
  6. Get involved, with a short "where we are" roadmap
  7. Useful numbers
- `evidence.html`, the evidence page. It has the figures and the detail for researchers and funders: what's changing, why a habit, fear and hate, the research, what we'll test, where 2ndScan fits, and what's next.
- `404.html`, the "page not found" page

## Other files

- `assets/style.css`: colours, fonts and layout for every page, including a dark mode
- `assets/img/`: photos, in two sizes each so phones download the smaller one
- `assets/fonts/`: Atkinson Hyperlegible Next and Bricolage Grotesque, with their licences (SIL Open Font License)
- `assets/favicon.svg`: the browser tab icon
- `SOURCES.md`: where every figure and phone number comes from, when it was checked, and which figures were left out and why
- `CNAME`: tells GitHub Pages to serve the site at 2ndscan.com (don't delete it)
- `.nojekyll`: tells GitHub to publish the files as they are
- `robots.txt`: lets search engines index the site

## Making a change

Ask Claude Code to edit the page and push the change, or edit a file directly on github.com and click **Commit changes**. The live site updates within a minute or two.

- **Contact email:** both pages use `hello@2ndscan.com`. Search for it and change every one.
- **Figures:** update the figure in `evidence.html`, then update `SOURCES.md` and the "checked" dates.

## Credits

- Photos: [A. C.](https://unsplash.com/photos/f5uc9of5eak) and [Vitaly Gariev](https://unsplash.com/photos/Gefm1M8kyjI) on Unsplash, used under the Unsplash License.
- Typefaces: Atkinson Hyperlegible Next (Braille Institute) and Bricolage Grotesque, both under the SIL Open Font License. The licence files are in `assets/fonts/`.
