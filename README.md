Theme Purchased from https://themeforest.net/item/lavar-portfolio-agency-jekyll-theme/15679321 - signed up as ajay610@gmail.com

Jekyll templates updated with ideas from https://github.com/uracreative/ura.design
Permission: https://github.com/uracreative/ura.design/issues/6

Install jekyll: https://jekyllrb.com/docs/installation/

```
gem install jekyll bundler

cd <WEBSITE>

bundle exec jekyll serve --host 0.0.0.0

# Install gems
bundle install

# Create a Gemfile
bundle init
# Add discovered dependencies
bundle add jekyll
bundle add jekyll-paginate
bundle add jekyll-compose
bundle install

# for the server to be available from outside:
bundle exec jekyll serve --host 0.0.0.0


# Probably not required!
# cannot load such file -- jekyll-paginate
gem install github-pages


```

## New Posts
New posts can be added by creating a new Markdown file (.md) inside the _posts directory. The file name should start with YYYY-MM-DD-post-name and have the .md extension in order to be recognized and for it to be live in the final website.

## Caching
There is caching applied on most of the static elements such as the logo, css and js files to increase the page access speed and lower overhead on the server (this also helps lower the total number of requests to the server by using locally cached files, read more [here](https://gtmetrix.com/leverage-browser-caching.html)).

