# David Jeehwan Lee: personal site

One page, no build step. Files:

| File | What it is |
| --- | --- |
| `index.html` | The whole site. Edit the `SITE` block to change text. |
| `images/headshot.jpg` | Your photo (keep the name, or change `photo` in `SITE`). |
| `cv.pdf` | The CV visitors can open. |
| `cv-1.png`, `cv-2.png` | Images of each CV page, shown in the in-page viewer. |

## Edit
1. Open `index.html` in a text editor (VS Code, or the pencil icon on GitHub).
2. Search for `EDIT YOUR SITE HERE`. Everything visitors read is in the `SITE` object below it.
3. Change text inside the quotes. Formatting: `**bold**`, `*italic*`, `==highlight==`, `[text](https://...)`.
4. Add an item by copying one `{ ... }` block and keeping the commas between blocks.
5. Hide a section: set it to `false` under `sections`.
6. Colors and fonts: the `:root` tokens at the top of `<style>` (light) and the two dark blocks right after.

## Preview
Double-click `index.html` to open it in a browser. Refresh after each save.

## Publish on GitHub Pages
1. Create a free GitHub account.
2. New repository named exactly `<your-username>.github.io`, set to Public.
3. Add file > Upload files: drag in everything in this folder (keep the `images` folder). Commit.
4. Settings > Pages: confirm it deploys from the `main` branch, root folder.
5. After a minute or two the site is live at `https://<your-username>.github.io`.
