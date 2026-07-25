Put your profile photo in this folder and name it "profile.jpg"
(or update the filename in index.html to match what you upload).

Recommended: a square photo, at least 500x500px, under 500KB.
# Md. Nasir Ahmed — Personal Website

A single-page personal/academic site built with plain HTML & CSS. White
background, image section in the hero, education timeline, research,
achievements, skills, activities, and contact/references.

## Files
- `index.html` — the page content
- `style.css` — all styling
- `images/` — put your profile photo here as `profile.jpg`

## Publish it on GitHub Pages

1. Create a new repository on GitHub (e.g. `nasir-ahmed-site`).
2. Upload these three items (`index.html`, `style.css`, `images/`) to the
   root of the repo — drag and drop them in via "Add file → Upload files",
   or push with git:
   ```
   git init
   git add .
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
   git push -u origin main
   ```
3. In the repo, go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to "Deploy from a branch",
   branch `main`, folder `/ (root)`. Save.
5. Wait 1–2 minutes. Your site will be live at:
   `https://YOUR-USERNAME.github.io/YOUR-REPO/`

## Add your photo
Upload a photo to the `images/` folder and name it `profile.jpg`
(or edit the `src="images/profile.jpg"` line in `index.html` to match
whatever filename you use). Until you add one, a placeholder box shows
instead.

## Editing content later
Everything in the page — text, dates, links — lives in `index.html`,
organized into clearly commented sections (About, Education, Research,
Achievements, Skills, Activities, Contact). Edit it directly on GitHub
using the pencil icon, commit, and the live site updates automatically.

