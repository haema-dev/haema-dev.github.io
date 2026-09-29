source "https://rubygems.org"

# Jekyll
gem "jekyll", "~> 4.4"

# Jekyll plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Windows and JRuby do not include zoneinfo files
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2.10"
  gem "tzinfo-data"
end

# Performance booster for watching directories on Windows
gem "wdm", "~> 0.2.0", install_if: Gem.win_platform?

# Web server
gem "webrick", "~> 1.9"