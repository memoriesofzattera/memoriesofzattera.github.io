source "https://rubygems.org"

gem 'github-pages', group: :jekyll_plugins

group :jekyll_plugins do
  gem "jekyll-paginate"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem 'wdm', '>= 0.1.0' if Gem.win_platform?
gem "kramdown", ">= 2.3.1"


gem "webrick", "~> 1.7"
gem 'jekyll-redirect-from'