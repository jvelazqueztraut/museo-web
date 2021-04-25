source "https://rubygems.org"
gem "jekyll", "~> 3.8.5"
gem "jekyll-theme-type", "~> 1.2"
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-paginate", "~> 1.1"
  gem "jekyll-tagging", "~> 1.1"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Add Rake to build static Jekyll site
gem "rake"
ruby "2.7.1"
