source "https://rubygems.org"

gem "jekyll", "~> 4.3.0"
gem "csv"
gem "logger"
gem "base64"

group :jekyll_plugins do
  gem "jekyll-remote-theme"
  gem "jekyll-feed"
  gem "jekyll-sitemap"
  gem "jekyll-seo-tag"
end

# Windows and JRuby does not include zoneinfo files
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]
