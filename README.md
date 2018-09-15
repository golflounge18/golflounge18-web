Theme Purchased from https://themeforest.net/item/lavar-portfolio-agency-jekyll-theme/15679321 - signed up as ajay610@gmail.com

Documentation: http://localhost:4000/doc/documentation.html

Jekyll templates updated with ideas from https://github.com/uracreative/ura.design
Permission: https://github.com/uracreative/ura.design/issues/6
Website: https://ura.design/

Theme for many xgolf centers: https://themesinfo.com/jupiter-child-wordpress-theme-rzh/latest
example: https://www.xgolfshelby.com/

## Tech notes
* Site switches between desktop and mobile at 1025 pixel width
    * Desktop styling: style.css
    * mobile styling: responsive.css

==================

## TODO
- Signup page needs formatting!
- Need event enquiry form
- Add signup page on Contact Us page
- Social media icon / links bigger
- Pages should have an image on the first 3rd of the page OR a background image
- Fix menus - add home, rates, convert contact to hierarchy
? Icon font for the whole website
- Add to rates:  
  - Kids membership
  - Family membership
  - Corporate memberships - reach out for memberships. 
  ? Free 30 minute swing analysis - introductory offer.
  ? Active Military discount 
- 404 must have a golf related image (see 404.html)
- Confirm / verify that google analytics still works (is includes/tracking.html used anywhere? - add to layouts): Should use Matomo? Its free! - removed Matomo code from footer.html
- Uncomment / Fix / Get testimonials on index.html
- All images must have an alt tag
- All pages must have tags, title, description - Define page.tags - see head.html for use / seo!
- Find/buy better stock photos
- Check XGolf Shelby and San Antonio location websites. 
- Fix desktop version
    - Phone number at top (for desktop version)
    - Top bar has a line through it!


## Getting Started

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

