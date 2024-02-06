source "https://rubygems.org"

gem "webrick", ">= 1.4"

# Use GitHub Pages
gem "github-pages", group: :jekyll_plugins

# Jekyll theme. You might not need to specify a version here.
# gem "minima"

# Plugins
group :jekyll_plugins do
  gem "jekyll-feed"
end

# Windows-specific gems
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
  gem "wdm", "~> 0.1.1"
end

# JRuby-specific gem
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
