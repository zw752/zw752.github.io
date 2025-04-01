source "https://rubygems.org"

# Use GitHub Pages gem to match their Jekyll environment
gem "github-pages", group: :jekyll_plugins

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Windows and JRuby support
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Windows file watching support
gem "wdm", "~> 0.1", platforms: [:mingw, :x64_mingw, :mswin]

# For JRuby
gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]
