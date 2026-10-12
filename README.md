# Pradyot Sharma — academic website

A static academic website ready for GitHub Pages. No build step or dependencies.

## Publish on GitHub Pages

1. Create a repository named `<your-GitHub-username>.github.io` for a personal homepage, or use another repository for a project website.
2. Upload the contents of this directory to the root of the repository, including `assets/` and `.nojekyll`.
3. In the repository, open **Settings → Pages**. Select **Deploy from a branch**, choose `main` and `/ (root)`, then save.
4. GitHub displays the website URL when deployment finishes.

All internal paths are relative, so both personal and project Pages URLs work. To use pradsharma.com, configure the custom domain in Pages settings and update DNS according to GitHub’s documentation; the CNAME file specifies www.pradsharma.com.

## Edit

- `index.html`: introduction and affiliations
- `research.html`: publications and work in progress
- `jmp.html`: job market paper, draft link, and coverage
- `teaching.html`: courses and teaching experience
- `cv.html`: education and appointments
- `assets/Pradyot-Sharma-CV.pdf`: downloadable original CV
- `assets/style.css`: visual design

Website prose omits co-author names except the JMP page, which credits T. Stratmann as requested. The downloadable CV is the original supplied document and retains its original credits. The JMP page includes the abstract posted on SSRN.

The homepage includes the supplied headshot and identifies the 2026–2027 academic job market. Update this line after the hiring cycle.

Design revision: white background, persistent profile sidebar, straightforward typography and navigation, with X and LinkedIn contact links.
