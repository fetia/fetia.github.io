# frozen_string_literal: true

source "https://rubygems.org"

# Jekyll core (4.x is required by Chirpy >= 5.4)
gem "jekyll", "~> 4.4", ">= 4.4.1"

# Use the Chirpy theme as a gem (recommended)
gem "jekyll-theme-chirpy", "~> 7.4"

# Sass pipeline: Jekyll 4 + Dart Sass (required by newer Chirpy)
gem "jekyll-sass-converter", "~> 3.1"
gem "sass-embedded", "~> 1.93"

# Plugins Chirpy relies on
gem "jekyll-include-cache", "~> 0.2"   # provides {% include_cached %}

# Common Jekyll extras (safe to include; Chirpy uses them)
gem "kramdown-parser-gfm", "~> 1.1"    # GitHub-flavored Markdown
gem "jekyll-paginate", "~> 1.1"        # pagination messages you saw
gem "jekyll-seo-tag", "~> 2.8"
gem "jekyll-sitemap", "~> 1.4"
gem "jekyll-feed", "~> 0.17"

# Needed to run `jekyll serve` on Ruby 3+
gem "webrick", "~> 1.8"

# Optional: silence Ruby 3.4 deprecation warnings you saw in CI
gem "csv", require: false
gem "base64", require: false

group :development do
  # For CI link checking (you run: bundle exec htmlproofer _site)
  gem "html-proofer", "~> 5.0"
end

