# frozen_string_literal: true

source "https://rubygems.org"

gem "jekyll"

group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-paginate"
  gem "tzinfo", platforms: [:mingw, :mswin, :x64_mingw, :ruby]
  gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :ruby]
  gem 'image_optim', platforms: [:mingw, :mswin, :x64_mingw, :ruby]
  gem 'image_optim_pack', platforms: [:mingw, :mswin, :x64_mingw, :ruby]
  gem "jekyll-jalali"
end

require 'rbconfig'
  if RbConfig::CONFIG['target_os'] =~ /darwin(1[0-3])/i
    gem 'rb-fsevent', '<= 0.9.4'
  end