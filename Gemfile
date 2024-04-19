# frozen_string_literal: true

source "https://rubygems.org"
gem "jekyll", "3.8.6"

group :jekyll_plugins do
    gem "autoprefixer-rails"
    gem "html-proofer"
    gem "image_optim"
    gem "jekyll-assets", git: "https://github.com/envygeeks/jekyll-assets"
    gem "jekyll-paginate"
    gem "jekyll-sitemap"
    gem "jemoji"
    gem "mini_magick"
    gem "sass"
    gem "sprockets", "~> 3.7"
    gem "uglifier"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?
