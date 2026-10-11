# Xiaohan Wang — Personal Website

Source for https://xiaohanwang1997.github.io/, built with Jekyll and Academic Pages.

## Where to edit

| Content | File or folder |
| --- | --- |
| About Me and education | `_pages/about.md` |
| Research page heading and layout | `_pages/research.html` |
| Mississippi Flood project | `_publications/mississippi-flood-occupational-mobility.md` |
| College financial aid project | `_publications/college-financial-aid.md` |
| Child labor laws project | `_publications/child-labor-occupational-mobility.md` |
| Courses and teaching awards | `_pages/teaching.md` |
| CV page and document link | `_pages/cv.md` |
| Top navigation | `_data/navigation.yml` |
| Sidebar, contact details, and site settings | `_config.yml` |
| Photos and image assets | `images/` |
| Locally hosted PDFs | `files/` |

## Folder organization

- `_pages/`: primary pages, with utility pages in `utility/` and template examples in `examples/`. Their explicit permalinks preserve their public addresses.
- `_publications/`: the three current research projects. Edit `title`, `excerpt`, and `keywords`; `order` controls display order. Explicit permalinks preserve the older paper URLs despite descriptive filenames.
- `_archive/duplicate-pages/`: previous competing Research and Teaching page templates, retained for reference and excluded from the website build.
- `docs/`: original Academic Pages documentation and contribution instructions, excluded from the website build.
- `_posts/`, `_drafts/`, `_talks/`, `_portfolio/`, and `_teaching/`: template collections; the current Teaching page lives in `_pages/teaching.md`.
- `_includes/`, `_layouts/`, `_sass/`, and `assets/`: shared rendering and styling files. Keep these standard Jekyll paths.
- `markdown_generator/`: optional template scripts for generating publication and talk entries; their sample data is not the current research content.
- `talkmap/`, `talkmap.py`, and `talkmap.ipynb`: talk-map assets and tooling. Their locations are retained for compatibility with the GitHub workflow.
- `.github/`: GitHub workflow and issue templates.

## Publishing changes

1. Review the Changes tab in GitHub Desktop.
2. Enter a short summary and commit to the current branch.
3. Click **Push origin**.
4. Wait for the GitHub Pages deployment to finish in the repository's Actions tab.

## Local preview

With Ruby and Bundler installed, run from the repository root:

```sh
bundle install
bundle exec jekyll serve
```

See [the original template documentation](docs/academicpages-template.md) for additional setup information.
