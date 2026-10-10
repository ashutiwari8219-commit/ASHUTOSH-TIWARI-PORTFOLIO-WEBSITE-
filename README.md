# Ashutosh Tiwari: The Series

A cinematic, series-style portfolio for **Ashutosh Tiwari**, an aspiring Data Analyst (Power BI, Python, SQL).
Every section is an episode, every project is an "Original", and the site plays like a series.

> A personal portfolio with a fictional streaming-series look. It is not affiliated with any streaming service and uses none of their logos.

## What's inside

- **Opening and "Who's watching?":** an intro sequence, then a viewer picker (Recruiter, Data team, Just browsing) that changes the order of the sections.
- **Hero:** name, role and summary.
- **The Pilot:** about me.
- **My Journey:** education and internships as seasons and episodes.
- **Originals:** project cards with dashboard screenshots. Each opens a detail view.
- **Skills:** grouped by area.
- **Certifications:** training and experience certificates.
- **Contact:** email, LinkedIn and GitHub.

## Tech

A single static file, `index.html`. No build step and no dependencies.

- HTML, CSS and vanilla JavaScript
- Fonts from Google Fonts (Bebas Neue and Inter), with system fallbacks
- Images are embedded in the file

## Run it locally

Open `index.html` in any browser. That's it.

## Deploy on Render (free Static Site)

1. Push this repository to GitHub with `index.html` in the root.
2. On [render.com](https://render.com), choose **New → Static Site** and connect the repository.
3. Settings:
   - **Branch:** `main`
   - **Build Command:** leave empty
   - **Publish Directory:** `.`
4. Click **Create Static Site**. Every push to `main` redeploys automatically.

It also works as-is on GitHub Pages, Netlify and Vercel.

## Updating the content

All content is in the `<script>` block near the bottom of `index.html`:

| To change... | Edit |
| --- | --- |
| A project, or a new one | the `projects` array |
| Internships and education | the `seasons` array |
| Skills | the `skills` object |
| Certifications | the `certs` array |
| Viewer profiles and section order | the `profiles` array |

Colors are CSS variables at the top of the `<style>` block (`--gold` is the accent).

## Contact

- Email: ashutiwari8219@gmail.com
- LinkedIn: https://linkedin.com/in/ashutosh-tiwari-cs
- GitHub: https://github.com/ashutiwari8219-commit
