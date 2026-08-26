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

## Notes

- The resume PDF lives at `assets/Resume_Galinato_Theo.pdf` and is linked from the
  Home and Resume pages — replace this file (keep the same name, or update the
  links) whenever you update your resume.
- To add real photos to the Leadership page, drop image files into `images/` and
  replace the `.photo-placeholder` divs in `leadership.html` with `<img src="images/yourphoto.jpg" alt="...">`.
- The site is fully responsive — nav collapses to a hamburger menu below 720px width.
