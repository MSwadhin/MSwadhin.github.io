# Abdullah Al Mujahid — Personal Website

A responsive, lightweight personal academic + engineering portfolio, ready for GitHub Pages. Pure HTML/CSS/JavaScript; no build step required.

## Publish it at https://mswadhin.github.io

1. Sign in to GitHub as **MSwadhin**.
2. Create a new **public** repository named **MSwadhin.github.io** (the name must match your account username, case-insensitively).
3. Upload **index.html**, **styles.css**, and **script.js** to the repository root (not inside the `mujahid-website` folder). Commit to the `main` branch.
4. Visit **Settings → Pages** for that repository. Under **Build and deployment**, choose **Deploy from a branch**, then **main** and **/(root)**, and save.
5. Visit **https://mswadhin.github.io/** after deployment finishes.

Alternatively, using Git (if the new empty repository exists):

```bash
cd mujahid-website
git init
git add index.html styles.css script.js README.md
git commit -m "Launch personal website"
git branch -M main
git remote add origin https://github.com/MSwadhin/MSwadhin.github.io.git
git push -u origin main
```

## Customize

- Update the About, Research, Experience, Projects, Achievements and Education content in `index.html`.
- The profile picture uses your public GitHub avatar URL; replace it with an image in your repo (e.g. `assets/profile.jpg`) if desired.
- Update color palette in `styles.css` (`:root`).
- Add verified publications, your CV PDF, and other academic links when ready.
- Contact address currently shown: `mujahid.swadhin@gmail.com` (from the connected GitHub account).

## Content sources

The detailed portfolio update uses:

- [Google Scholar](https://scholar.google.com/citations?user=t8Xy_fAAAAAJ&hl=en) for publication metadata.
- Linked arXiv papers and conference records for research summaries and publication status.
- The official ICPC 2021 World Finals brochure for AIUB_Captured's team roster.
- The Codeforces profile for the peak rating of 1927.
- AIUB's Intra AIUB Programming Contest 2024 report for coaching and contest-hosting involvement.
- The author's LinkedIn profile and award announcement for the continental-finals result and leadership award.

The supplied public Notion page's headings were accessible, but subsequent attempts to expand its sections were rate-limited. Existing employment dates, project areas, and the mentoring count were retained from the original portfolio; these were not independently reverified from the expanded Notion page. Citation counts are intentionally not hardcoded.

The page distinguishes conference publications from the arXiv preprint and links to the source records. The ICPC 2021 World Finals took place in November 2022.
