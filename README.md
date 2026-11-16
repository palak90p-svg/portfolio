# Palak Pandey | Portfolio Website

A single-page portfolio built with only HTML5, CSS3 and vanilla JavaScript. No framework, no build step, ready for GitHub Pages.

## Folder structure

```
portfolio/
├── index.html
├── css/style.css
├── js/script.js
├── assets/
│   ├── images/profile.jpg
│   └── documents/resume.pdf
└── README.md
```

## Test locally

**Option 1 (simplest):** double-click `index.html`. It opens in your browser.

**Option 2 (VS Code Live Server):**
1. Open the `portfolio` folder in VS Code.
2. Install the "Live Server" extension.
3. Right-click `index.html` and choose "Open with Live Server".

Check: dark/light toggle, mobile menu (make the window narrow), the Download Resume button, and all links.

## Deploy on GitHub Pages

1. Sign in at https://github.com and click **New repository**.
2. Name it `YOUR-USERNAME.github.io` (for a clean address) or any name such as `portfolio`. Keep it **Public** and click **Create repository**.
3. Click **uploading an existing file**. Upload the **contents** of the `portfolio` folder (`index.html`, `css`, `js`, `assets`, `README.md`), not the outer folder itself. `index.html` must be at the top level of the repository.
4. Click **Commit changes**.
5. Go to **Settings > Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, Branch to **main**, folder **/ (root)**, then **Save**.
6. Wait 1 to 2 minutes and refresh. Your site is live at:
   - `https://YOUR-USERNAME.github.io/` (if the repo is named `YOUR-USERNAME.github.io`)
   - `https://YOUR-USERNAME.github.io/REPO-NAME/` (for any other repo name)

To update later, open a file on GitHub, click the pencil icon, edit, and commit. Changes appear in a minute or two.

## What to replace or add later

| Item | Where | What to do |
|---|---|---|
| GitHub profile link | `index.html`, Contact section | Remove `hidden` from the GitHub `<li>` and replace `YOUR-USERNAME` |
| Project GitHub / Live Demo | `index.html`, Featured Project | Remove `hidden` from the buttons and put real URLs in `href` |
| Project report PDF | `index.html` | Save as `assets/documents/project-report.pdf`, then remove `hidden` from that button |
| Project screenshot | `index.html`, project visual | Replace the SVG `<figure>` with an `<img>` (see the comment in the file) |
| Extra role details | `index.html`, "My role" list | Add what else you personally did on the project |
| Social preview | `<meta property="og:url">` | Uncomment and set your live site URL |
| Resume | `assets/documents/resume.pdf` | Replace the file, keeping the same name |

## Notes

- The project is presented as an academic concept: tools are labelled "proposed" and the sample table is labelled "Illustrative sample, not a measured result".
- Keep the project honest: once you build it, change "proposed" to "used" and add your GitHub link.
