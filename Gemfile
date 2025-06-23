source "https://rubygems.org"

# GitHub Pages gem bundle
gem "github-pages", group: :jekyll_plugins

# Cross-platform fixes
gem "tzinfo-data" # Needed on Windows
gem "wdm", "~> 0.1.0" if Gem.win_platform?

# Jekyll plugins (additional functionality)
group :jekyll_plugins do
  gem "jekyll-paginate"
  gem "jekyll-sitemap"
  gem "jekyll-gist"
  gem "jekyll-feed"
  gem "jemoji"
  gem "jekyll-include-cache"
  gem "jekyll-algolia" # Optional: only use if you're setting up Algolia search
end
