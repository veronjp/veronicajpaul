# Veronica J. Paul

An independent lab notebook for experiments, research, writing, and explorations of psychology, cognition, behavioural science, AI, and human behaviour.

**Live site:** https://veronjp.github.io/veronicajpaul/

## Site structure

- `_experiments/`: individual experiment pages
- `experiments/`: experiments index
- `_research/`: individual research items
- `research/`: research index
- `_posts/`: Jekyll writing posts
- `writing/`: writing index
- `about/`: About page
- `contact/`: contact page (the Formspree form lives here)
- `_layouts/`: shared page layouts (`default`, and `prose` for Markdown pages)
- `_includes/`: shared header, footer, and the image card used on the homepage and Experiments page
- `_data/social.yml`: footer social links (a link appears once its `url` is filled in)
- `assets/css/style.css`: global design system and styling (colours, type, and spacing are tokens at the top)
- `assets/js/nav.js`: mobile menu
- `assets/images/`: local card illustrations

## Local development

```
bundle install
bundle exec jekyll serve
```

The local site runs at `http://127.0.0.1:4000/veronicajpaul/`.

## Deployment

The site is deployed through GitHub Pages from the `main` branch. The legacy wellbeing survey pages remain available at their existing URLs.