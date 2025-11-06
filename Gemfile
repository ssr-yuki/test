source 'https://rubygems.org'

gem "jekyll", "~> 4.2"

gem "jekyll-scholar", git: 'https://github.com/inukshuk/jekyll-scholar.git'
gem "jekyll-theme-clean-blog", git: 'https://github.com/StartBootstrap/startbootstrap-clean-blog-jekyll.git'

group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-paginate"
  gem "jekyll-sitemap"
end

# To avoid v1.93.3, causing errors on GitHub Action
gem "sass-embedded", "<= 1.93.2"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Performance-booster for watching directories on Windows
gem "wdm" if Gem.win_platform?
