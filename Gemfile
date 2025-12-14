# frozen_string_literal: true

source "https://rubygems.org"

# Note: This site now uses .nojekyll to skip Jekyll processing
# Jekyll dependencies below are kept only for local development/testing if needed

gem "jekyll", "~> 4.3.0"

group :jekyll_plugins do
  gem "jekyll-sitemap"
end

# Lock ffi to compatible version to avoid rubygems version conflicts
gem "ffi", "~> 1.15.0"

# Windows and JRuby platforms
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

