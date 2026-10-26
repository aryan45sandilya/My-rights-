# My Rights, My Ward

A bilingual (English and Hindi) guide to patients' rights on a mental health ward under India's Mental Healthcare Act, 2017, with a complaint form, a Review Board application, tools and a learning game.

Prototype for a Mental Health Laws assignment. A guide, not legal advice.

## Put it online for free

Upload **everything in this folder** (not the folder's parent) to one of these.

### Option 1: Netlify Drop (quickest, no Git)

1. Go to https://app.netlify.com/drop
2. Drag this whole folder onto the page.
3. Netlify gives you a public link. If it asks you to claim the site, sign up for a free account so the site stays online. You can rename the link in the site settings.

### Option 2: GitHub Pages

1. On GitHub, create a new **public** repository, for example `my-rights-my-ward`.
2. Choose **Add file → Upload files**, drag in all the files from this folder, and commit.
3. Open **Settings → Pages**. Under **Build and deployment**, set **Source** to *Deploy from a branch*, choose the `main` branch and the `/ (root)` folder, and save.
4. After a minute or two the site is live at `https://<your-username>.github.io/my-rights-my-ward/`.

## What's in the folder

| File | What it does |
|---|---|
| `index.html` | The whole app, plus a reading version for viewers that block JavaScript |
| `sw.js` | Lets the site open offline after the first visit |
| `manifest.webmanifest`, icons | Let phones install it to the home screen like an app |

## After it's live

- Open the **Tools → Ward poster** tool: the QR code fills in the site's own address automatically.
- Add `#help`, `#complain`, `#what`, `#tools` or `#game` to the address to open that tab directly.
- To update the site, replace `index.html` with the new version and upload again.
