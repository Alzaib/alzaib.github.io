# Portfolio (static site)

Plain HTML and CSS. No JavaScript, no external requests, no analytics, no API keys.

## Structure
- `index.html`: introduction and project list
- `projects/<slug>/index.html`: one detailed report per project
- `assets/<slug>/`: that project's images and GIFs
- `_template/project.html`: copy to `projects/<new-slug>/index.html` to add a project, then add a card to `index.html`
- `style.css`: shared styles

## Publish safely
1. Create a **private** repo on GitHub (do not tick "Add a README"). Keep it private until you are happy with the content.
2. Before every commit run `git status` and check no `.env`, key or token files are listed.
3. Turn on Pages (Settings > Pages) only when you want the site public. Pages from a private repo needs a paid GitHub plan; on the free plan the site is public once Pages is on.
4. Replace the bracketed placeholders before going public. Use a public contact link, not your phone or home address.
