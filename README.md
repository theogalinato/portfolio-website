# Theo Galinato — Portfolio Site

A 6-page personal portfolio built with plain HTML/CSS/JS (no build tools needed) in a
dark, tech-inspired style. Pages: Home, Resume, Projects, Leadership, Outside Work, Contact.

## Files

```
portfolio-site/
├── index.html          Home / About
├── resume.html          Resume (education, experience, skills)
├── projects.html       Projects
├── leadership.html     Leadership / Involvement
├── outside.html        Outside Work / Fun
├── contact.html        Contact
├── css/style.css        All styling
├── js/script.js         Mobile nav toggle + active link highlight
├── assets/               Your resume PDF goes here
└── images/                Photos for the Leadership page go here
```

## Before you publish

Look for the yellow `✏️ EDIT ME` boxes on the Projects, Leadership, Outside Work,
and Contact pages — those mark placeholder content pulled from what you gave me
(project names, generic descriptions, blank social links). Fill those in with your
real details, links, and photos before sharing the site.

## Running it locally in VS Code

1. Open the `portfolio-site` folder in VS Code (`File > Open Folder…`).
2. Install the **Live Server** extension (search "Live Server" by Ritwick Dey in
   the Extensions panel).
3. Right-click `index.html` → **Open with Live Server**. It'll open in your
   browser and auto-refresh as you edit.

## Publishing with GitHub Pages

1. **Create a new repository** on GitHub — e.g. `theo-portfolio` (public, no README/gitignore needed since you already have files).
2. **Initialize git in this folder and push**, from a terminal opened in the `portfolio-site` folder:

   ```bash
   git init
   git add .
   git commit -m "Initial portfolio site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-repo-name>.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to your repo on GitHub → **Settings** → **Pages** (left sidebar).
   - Under **Build and deployment** → **Source**, choose **Deploy from a branch**.
   - Under **Branch**, choose `main` and folder `/ (root)`, then **Save**.
   - GitHub will give you a URL like `https://<your-username>.github.io/<your-repo-name>/`
     — it usually takes 1–2 minutes to go live after the first deploy.

4. **Future updates**: after editing files locally, just run:

   ```bash
   git add .
   git commit -m "Update projects page"
   git push
   ```

   GitHub Pages automatically redeploys on every push to `main`.

## Notes

- The resume PDF lives at `assets/Resume_Galinato_Theo.pdf` and is linked from the
  Home and Resume pages — replace this file (keep the same name, or update the
  links) whenever you update your resume.
- To add real photos to the Leadership page, drop image files into `images/` and
  replace the `.photo-placeholder` divs in `leadership.html` with `<img src="images/yourphoto.jpg" alt="...">`.
- The site is fully responsive — nav collapses to a hamburger menu below 720px width.
