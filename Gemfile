# frozen_string_literal: true

source "https://rubygems.org"

# Main Jekyll engine (compatible version for Chirpy 7.4)
gem "jekyll", "~> 4.3.3"

# Theme
gem "jekyll-theme-chirpy", "~> 7.4"

# Plugins used in your _config.yml
gem "jekyll-paginate"
gem "jekyll-seo-tag"
gem "jekyll-sitemap"
gem "jekyll-feed"
gem "jekyll-include-cache"
gem "jekyll-redirect-from"

# Optional: suppress Ruby 3.4 warnings
gem "csv", require: false
gem "base64", require: false

# GitHub Pages (not needed if you build via Actions)
# gem "github-pages", group: :jekyll_plugins

# Windows-specific fix (safe to keep on all OS)
gem "wdm", "~> 0.1.1", platforms: [:mingw, :x64_mingw, :mswin]

group :development do
  gem "webrick", "~> 1.8"
end
