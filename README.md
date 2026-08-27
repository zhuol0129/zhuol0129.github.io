# Zhuo (Zoe) Li — Personal Website

Plain HTML/CSS, no build step, no dependencies. This README walks you through putting it on GitHub Pages and making edits later.

## What's in this folder

All files sit flat in one folder (no subfolders) so you can upload them to GitHub one by one — GitHub's web uploader doesn't accept dragging in a whole folder unless your browser supports folder drag-and-drop, so flat is the reliable option.

```
index.html              → the whole page (all sections)
style.css                → all styling/colors/layout
avatar-placeholder.svg   → placeholder photo (swap for a real headshot anytime)
academic-cv.pdf          → your Academic CV, already included
resume.pdf               → NOT included yet — add your final resume PDF here (see below)
README.md                → this file
```

---

## Part 1 — Get a free GitHub account

1. Go to github.com and click "Sign up" if you don't already have an account.
2. Verify your email. You now have a GitHub account — this is where your website's files will live and where GitHub Pages will publish them from.

---

## Part 2 — Create the repository

A "repository" (repo) is just a project folder on GitHub.

1. Once logged in, click the **+** icon in the top right → **New repository**.
2. Name it exactly: `zhuoli.github.io` — replace `zhuoli` with your actual GitHub username, all lowercase. (This exact naming pattern — `username.github.io` — is what makes GitHub host it at that clean URL automatically. If you use any other repo name, your site will still work, just at `username.github.io/repo-name` instead.)
3. Leave it **Public** (GitHub Pages requires this on free accounts).
4. Do NOT check "Add a README" — we already have one.
5. Click **Create repository**.

---

## Part 3 — Upload the files

Easiest way, no command line needed:

1. On your new repo's page, click **uploading an existing file** (or "Add file" → "Upload files").
2. Select or drag in ALL the files at once: `index.html`, `style.css`, `avatar-placeholder.svg`, `academic-cv.pdf`, and `README.md` (and `resume.pdf` once you have it). You can select multiple files at once in the file picker — hold Ctrl (Windows) or Cmd (Mac) while clicking each one, or select them all with a drag-select, then choose "Open."
3. Scroll down, click **Commit changes**.

Your repo should now show all those files listed at the top level — no folders needed.

---

## Part 4 — Turn on GitHub Pages

1. In your repo, click **Settings** (top menu bar of the repo, not your account settings).
2. In the left sidebar, click **Pages**.
3. Under "Build and deployment" → "Source", choose **Deploy from a branch**.
4. Under "Branch", choose **main** and folder **/ (root)**, then click **Save**.
5. Wait about 1-2 minutes. Refresh the Pages settings screen — you'll see a green box: "Your site is live at https://yourusername.github.io/".
6. Click that link. Your site is now public.

---

## Part 5 — Add your real photo and resume

- **Photo**: get a square-ish photo of yourself, rename it `headshot.jpg` (or `.png`), upload it into the repo (same "Add file → Upload files" flow, dropped at the top level like everything else). Then edit `index.html`: find the line near the top of the `<aside class="sidebar">` section that says
  `<img class="avatar" src="avatar-placeholder.svg" ...>`
  and change `avatar-placeholder.svg` to `headshot.jpg`. Commit the change — GitHub Pages updates automatically within a minute.
- **Resume**: once you have your final resume PDF, upload it to the repo (top level) and name it exactly `resume.pdf` (this matches what `index.html` already links to, so no code edit needed — just upload the file with that name).

---

## Part 6 — Making edits later

You have two options:

**Option A — edit directly on GitHub.com (easiest, no setup):**
1. Open the repo, click on `index.html`.
2. Click the pencil icon (Edit this file) in the top right.
3. Find the text you want to change (Ctrl/Cmd+F works in the editor), edit it, scroll down, click **Commit changes**.
4. Your live site updates within about a minute.

**Option B — edit locally on your computer (better if you're making a lot of changes):**
1. Install [GitHub Desktop](https://desktop.github.com/) (a simple app, no command line).
2. Open it, sign in, and "Clone" your `zhuoli.github.io` repo to your computer.
3. Open `index.html` in any text editor (even TextEdit/Notepad, or something nicer like VS Code) and make changes.
4. Save the file, go back to GitHub Desktop — it shows what changed — write a short summary and click "Commit to main", then "Push origin".
5. Your live site updates within about a minute.

### Common edits and where to find them in `index.html`

- **Bio text** — look for `<section id="about"` and the `<p class="bio">` paragraph right after it.
- **Add a new research or work experience entry** — look for `<section id="research"` or `<section id="experience"`, find an existing `<div class="entry">...</div>` block, and copy/paste one as a template, then edit the text inside.
- **Add/remove a hobby tile** — look for `<section id="hobbies"`, find `<div class="hobby-tile">...</div>` blocks — copy one to add a new hobby, delete one to remove.
- **Change colors** — open `style.css`, edit the values at the very top under `:root { ... }`. `--accent` is the one accent color used throughout (currently a deep indigo, `#2A3B8F`).
- **Change the font** — same `:root { ... }` block in `style.css`, edit `--font-family`. It's currently set to `'Times New Roman', Times, Georgia, serif`. List your preferred font first, then a couple of fallbacks in case a visitor's device doesn't have it — e.g. for a sans-serif look you could use `--font-family: Arial, Helvetica, sans-serif;`. Any font already installed on most computers (Arial, Georgia, Verdana, Helvetica, Times New Roman, Courier New) works this way with no extra setup. If you want a *specific* Google Font (like Inter, or something more distinctive), that needs one extra step: add a `<link>` for it in the `<head>` of `index.html` (Google Fonts' site gives you the exact line to paste) and then reference that font's name in `--font-family`.
- **Change the footer year** — open `index.html`, search for `© 2026 Zhuo (Zoe) Li` near the very bottom.

### The general pattern for "how do I change X"

Every piece of text you see on the page lives in `index.html` — search for the exact words you want to change (Ctrl/Cmd+F in whatever editor you're using) and edit them directly between the `<tags>`. Every visual style (colors, spacing, fonts, sizing) lives in `style.css` — each HTML element has a `class="..."` name, and that same name appears in `style.css` with the rules that control how it looks. So the loop is: find the text or section in `index.html` → note its `class` name if you want to restyle it → find that class in `style.css` → change the value → save → re-upload (or commit) → refresh the live site. Nothing here needs a build step, so every change is just "edit → save → upload."

That's it — no build tools, no npm, no compiling. Edit the HTML/CSS, save, commit, and it's live.
