# Tye Hickman — personal site

A Jekyll site for notes, projects, and stories across software engineering, game development, hobby robotics, and creative writing.

## Theme boundary

`assets/css/vendor/grimmoire.css` is the generated Grimmoire Web 0.1.0 artifact from the separate Grimmoire Theme project. Its banner records the source revision. Site structure and local components live in `assets/css/site.css`, which loads after the vendor layer.

The artifact is vendored locally until the first public Grimmoire Theme release. Once release assets exist, a manual GitHub Actions workflow will update it through a reviewable pull request.

## Local preview

Use the GitHub Pages dependency set declared in `Gemfile`:

```sh
bundle install
bundle exec jekyll serve
```
