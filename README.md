# rayankhan06.github.io

My personal portfolio site, built to showcase projects and leadership work as a CS student at NJIT. Live at [rayankhan06.github.io](https://rayankhan06.github.io).

## About

Single-page site, no framework or build step. Styled around a terminal / commit-log theme: the hero reads like a shell session, projects are laid out like a commit log, and leadership is framed as dated release notes.

## Stack

- Plain HTML, CSS, and vanilla JS in one file (`index.html`)
- Google Fonts (IBM Plex Mono, IBM Plex Sans)
- No build tools, no dependencies, deployed directly via GitHub Pages

## Structure

```
index.html   # the entire site
README.md    # this file
_config.yml  # GitHub Pages config
```

## Editing

All content lives in `index.html`. Look for `<!-- EDIT: -->` comments marking spots meant to be personalized or updated (contact info, project entries, leadership entries).

To add a new project, duplicate one of the `.commit` blocks in the `projects/` section. To add a new leadership or achievement entry, duplicate one of the `.release` blocks in the `leadership/` section.

## Deployment

Pushes to `main` deploy automatically via GitHub Pages. No CI/build step required, since it's a static file.

## License

Personal site, all rights reserved on original content. Feel free to use the structure/styling as a template for your own portfolio.
