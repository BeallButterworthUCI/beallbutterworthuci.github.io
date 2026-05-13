# BeallButterworthUCI.github.io

Public site for the UCI Beall Butterworth Competition Historical Archive.

The site is the rendered, design-polished surface of the citation-backed data and prose maintained in the companion repository: [BeallButterworthUCI/History](https://github.com/BeallButterworthUCI/History).

## Stack

- **Jekyll 4** (`_config.yml`, `_layouts/`, `_includes/`)
- Plain CSS hand-crafted around a UCI navy + gold palette
- Per-year content lives in `_years/*.md` and is rendered via the `year` layout

## Local development

```bash
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>.

## Content

- Everything published here traces to a primary source documented in [BeallButterworthUCI/History](https://github.com/BeallButterworthUCI/History).
- Only public information is published. Personal contact info, unconfirmed rumors, and private business details are excluded.

## Contributing

To fix a typo or refresh a fact, open a PR. To correct or expand the underlying historical record, please contribute to the [archive repository](https://github.com/BeallButterworthUCI/History) so the change flows everywhere.
