# frozen_string_literal: true
source "https://rubygems.org"

# --- Core engine ---
gem "jekyll", "= 4.3.3"

# --- Theme ---
gem "jekyll-theme-chirpy", "= 7.3.2"

# --- Jekyll plugins (used in your _config.yml) ---
gem "jekyll-paginate"
gem "jekyll-seo-tag"
gem "jekyll-sitemap"
gem "jekyll-feed"
gem "jekyll-include-cache"
gem "jekyll-redirect-from"

# --- Silence Ruby 3.4 deprecation warnings ---
gem "csv", require: false
gem "base64", require: false

# --- Development helper (needed for local serve) ---
group :development do
  gem "webrick", "~> 1.8"
end

# --- Windows support (safe to keep) ---
gem "wdm", "~> 0.1.1", platforms: [:mingw, :x64_mingw, :mswin]
