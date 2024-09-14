source "https://rubygems.org"

ruby ">=2.6"

gem "jekyll", "~> 3.9.0"
gem "kramdown-parser-gfm", "~> 1.1.0"

group :locked_because_old_rubygems do
  gem "ffi", "< 1.17"
end

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.6"
  gem 'jekyll-seo-tag'
end

gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem "wdm", "~> 0.1.0" if Gem.win_platform?
