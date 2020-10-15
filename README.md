### little j studio - teaser website

Teaser website, showing a small portfolio of work and contact information.


#### Dev instructions

To run locally:
* `bundle install`
* `bundle exec jekyll serve`
* Visit localhost:4000

#### Deploying with github pages

The _site/ directory of this repo is served as the source.

Github pages serves the `gh-pages` branch of the repo.

In order to update the source:
* `bundle exec jekyll build` or `bundle exec jekyll serve`
* Push updated _site directory to branch with: `git subtree push --prefix _site/ origin gh-pages`
