# frozen_string_literal: true
source "https://rubygems.org"

# Core Jekyll engine
gem "jekyll", "= 4.3.3"

# Chirpy theme (stable, compatible with Jekyll 4.3)
gem "jekyll-theme-chirpy", "= 7.3.1"

# Common Jekyll plugins
gem "jekyll-paginate"
gem "jekyll-redirect-from"
gem "jekyll-seo-tag"
gem "jekyll-sitemap"
gem "jekyll-feed"
gem "jekyll-include-cache"

# Fix Ruby 3.4 warnings
gem "csv", require: false
gem "base64", require: false

# Development server for local preview
group :development do
  gem "webrick", "~> 1.8"
end

# Optional (for Windows compatibility)
gem "wdm", "~> 0.1.1", platforms: [:mingw, :x64_mingw, :mswin]
