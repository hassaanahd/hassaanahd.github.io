# hassaanahd.github.io

Personal academic website of Hassaan Ahmed, built on the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template.

## Where things live

| What | File |
| --- | --- |
| Name, sidebar bio, email, profile links | `_config.yml` (the `author:` block) |
| Profile photo | `images/profile.png` |
| Menu order | `_data/navigation.yml` |
| Homepage (bio, interests, news) | `_pages/about.md` |
| Research | `_pages/research.md` |
| Publications | one file per paper in `_publications/` |
| Teaching | `_pages/teaching.md` |
| CV | `_pages/cv.md` (PDF goes in `files/cv.pdf`) |
| Reading list | `_pages/reading.md` |
| Custom styles | `_sass/layout/_custom.scss` |

## Adding a publication

Copy `_publications/2026-01-01-dmdc-groundwater.md`, change the date in the filename and the front matter, and fill in `title`, `venue`, `citation` and, when available, `paperurl`.

## Deploying

The site is built by the GitHub Actions workflow in `.github/workflows/jekyll.yml` on every push to `main`. In the repository's **Settings → Pages**, the source must be set to **GitHub Actions**.
