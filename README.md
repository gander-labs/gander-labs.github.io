# gander-labs.github.io

Landing page for the [gander-labs](https://github.com/gander-labs) organization, published at <https://gander-labs.github.io/>.

gander-labs hosts experiments, prototypes and early-stage projects by [gander](https://github.com/gander). Projects start as private repositories and appear on the page once they are made public.

## Development

The site is built by GitHub Pages with [Jekyll](https://jekyllrb.com/). Projects are listed, in groups, in `_data/projects.yml`; add an entry there to show a new project on the page. Only public repositories belong on the page; while the list is empty, the page shows a note instead.

```sh
bundle install
bundle exec jekyll serve
```
