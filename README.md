# xavierbouclet.com

Source of my personal blog, [www.xavierbouclet.com](https://www.xavierbouclet.com): posts, talks and courses about Java, Kotlin and Spring Boot.

The site is built with [Jekyll](https://jekyllrb.com/) and [jekyll-asciidoc](https://github.com/asciidoctor/jekyll-asciidoc). The theme is based on [Clean Blog](https://startbootstrap.com/themes/clean-blog-jekyll/) by Start Bootstrap (MIT, see [LICENSE](LICENSE)).

## Run locally

```bash
bundle install
bundle exec jekyll serve
```

The site is then available on http://127.0.0.1:4000.

## Content

- `_posts/`: blog posts, named `YYYY-MM-DD-title.adoc`
- `_conferences/`: talks, listed on the Talks page; slides (PDF) go in `conferences/`
- `_courses/`: courses, listed on the Courses page
- `img/`: images, with post images in `img/posts/`

## Deployment

Every push to `main` builds the site and deploys it to GitHub Pages through the GitHub Actions workflow in `.github/workflows/`.
