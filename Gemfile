# frozen_string_literal: true

source "https://rubygems.org"
gem "jekyll", "~> 3.9"

group :jekyll_plugins do
    gem "autoprefixer-rails", "~> 10.4"
    gem "html-proofer", "~> 5.0"
    gem "image_optim", "~> 0.31"
    gem "jekyll-assets", git: "https://github.com/envygeeks/jekyll-assets", branch: "master"
    gem "jekyll-paginate", "~> 1.1"
    gem "jekyll-sitemap", "~> 1.4"
    gem "jemoji", "~> 0.13"
    gem "mini_magick", "~> 4.12"
    # gem "sass", "~> 3.7"
    gem "uglifier", "~> 4.2"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?
