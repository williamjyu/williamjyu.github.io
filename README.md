# williamjyu.github.io

Personal website of William Yu, live at <https://williamjyu.github.io>.

Built with [Jekyll](https://jekyllrb.com/) on the [al-folio](https://github.com/alshedivat/al-folio) template, with a custom
light theme ("Skyspace at dusk") in `_sass/_turrell.scss`.

## Local preview

```bash
docker compose pull
docker compose up -d
open http://localhost:8080
```

## Where things live

| What              | File                                     |
| ----------------- | ---------------------------------------- |
| About (home)      | `_pages/about.md`                        |
| Work              | `_pages/work.md`                         |
| Projects          | `_pages/projects.md` + `_projects/*.md`  |
| Misc              | `_pages/misc.md`                         |
| Social links      | `_data/socials.yml`                      |
| Resume            | `assets/pdf/resume.pdf`                  |
| Profile photo     | `assets/img/prof_pic.jpg` (see about.md) |
| Theme colors/glow | `_sass/_turrell.scss`                    |

Placeholder copy is marked with `PLACEHOLDER`; find it all with `grep -rn PLACEHOLDER _pages _projects _data _config.yml`.

Pushing to `main` deploys to GitHub Pages via `.github/workflows/deploy.yml`.
