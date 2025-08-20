source "https://rubygems.org"

# Core
gem "jekyll", "~> 4.2"
gem "webrick"            # needed for `jekyll serve` on Ruby 3.x
gem "logger"

# Plugins (keep it light)
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.17"
  gem "jekyll-seo-tag", "~> 2.8"
end

# Windows time zone data (no need to pin tzinfo v1)
platforms :windows, :jruby do
  gem "tzinfo-data"
end
