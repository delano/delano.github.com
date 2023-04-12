source "https://rubygems.org"

gem "rubygems-update", "~> 3.4"

gem "jekyll", "~> 4.3"

# Jekyll plugins are loaded right after jekyll itself so any plugin that
# adds a new command, overrides a default Jekyll class or modifies liquid
# tags/filters must be listed here.
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem 'jekyll-timeago', '~> 0.13.1'
end

# Use unreleased minima v3 theme
# See: https://github.com/jekyll/minima/tree/2863624b903b17f838d6ce8d2f77900fa9d3c864#readme
gem "minima", git: 'https://github.com/jekyll/minima.git', ref: '2863624b90'
