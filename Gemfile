source "https://rubygems.org"

gem "jekyll", "~> 4.1"
#gem "github-pages", group: :jekyll_plugins

gem "jekyll-remote-theme"

group :jekyll_plugins do
  gem "jekyll-sitemap", "~> 1.4.0"
  gem "jekyll-mentions", "~> 1.6.0"
  gem "jekyll-paginate", "~> 1.1.0"
  gem "jekyll-seo-tag", "~> 2.7.1"
  gem "jekyll-redirect-from", "~> 0.16"
  gem "jekyll-feed", "~> 0.15"
  gem "jekyll-commonmark", "~> 1.3.1"
  gem "jekyll-include-cache", "~> 0.2"
  gem "jemoji", "~> 0.12"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]


