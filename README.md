# BeallButterworthUCI.github.io

The public site for the UCI Beall Butterworth Competition historical archive.

Lives at <https://beallbutterworthuci.github.io>.

The site renders the citation-backed data and prose maintained in the companion archive repo: [BeallButterworthUCI/History](https://github.com/BeallButterworthUCI/History).

## Stack

Jekyll 4. Plain CSS. No build step beyond GitHub Pages.

## Run it locally

```
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>.

## Layout

```
_config.yml
_layouts/         default and year layouts
_includes/        header and footer partials
_years/           one markdown file per cycle (2010 through 2026)
assets/css/       the single stylesheet
index.html        landing page
about.md          about page
companies.md      verified active companies
alumni.md         where alumni went after BBComp
faculty.md        recurring faculty mentors
patrons.md        the Butterworth and Beall families
stories.md        deep-dive case studies
timeline.md       the eras narrative
404.html          fallback
```

## Contributing

To fix a typo or update the site, open a PR here.

To correct or expand the underlying historical record, please contribute to the [archive repo](https://github.com/BeallButterworthUCI/History) so the change flows everywhere.

Only public information goes on the site.
