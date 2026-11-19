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
- The portrait is stored locally at `assets/portrait.jpg`. Source: [Bangladesh Competitive Programming Society](https://therealbcs.com/icpc), where it is labeled Abdullah Al Mujahid.
- Update color palette in `styles.css` (`:root`).
- Add verified publications, your CV PDF, and other academic links when ready.
- Contact address currently shown: `amgzc@mst.edu` (from the connected GitHub account).

## Content sources

The detailed portfolio update uses:

- [Google Scholar](https://scholar.google.com/citations?user=t8Xy_fAAAAAJ&hl=en) for publication metadata.
- Linked arXiv papers and conference records for research summaries and publication status.
- The official ICPC 2021 World Finals brochure for AIUB_Captured's team roster.
- The Codeforces profile for the peak rating of 1927.
- AIUB's Intra AIUB Programming Contest 2024 report for coaching and contest-hosting involvement.
- The author's LinkedIn profile and award announcement for the continental-finals result and leadership award.

Experience, teaching, contest results, and judging details were checked against the user's local Notion download (`notion/Abdullah Al Mujahid.html`). The download is excluded from Git and deployment. Its older “Present” labels were not used to change the existing employment end dates. The Deepchain internship is intentionally omitted at the user's request. The number-plate recognition work is described without numerical performance claims.

The page distinguishes conference publications from the arXiv preprint and links to the source records. The ICPC 2021 World Finals took place in November 2022.

## Editorial style

Use short, factual sentences. Keep Research, Experience, Competitive Programming, Service, Interests, and Contact. Use “PhD student” for academic status and “researcher” for the research role; never “PhD researcher”. Avoid slogans, team rosters, GitHub project promotion, and repeated profile links. Keep paper titles and author lists complete.

The MSR 2027 Junior Program Committee role, research focus, current interests, and university email were supplied directly by the owner. The Codeforces maximum rating is included; other online profiles are linked without ratings.

Latest owner-supplied updates: the first manuscript is submitted to *Empirical Software Engineering* (EMSE), not accepted; the leadership award was received in 2023; Shift IT Solutions operated from 2016 to 2018. Mentorship is listed under Service. Only the personal email address appears in Contact.
