source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.4.3"

gem "rails", "~> 8.0.0"

gem "puma", "~> 6.4"

gem "bootsnap", require: false

gem "importmap-rails"
gem "sprockets-rails"
gem 'dartsass-rails', '~> 0.5.0'

gem 'country_select'

gem 'simple_form'
gem 'formtastic'

group :development, :test do
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
end

group :development do
  gem "web-console"
end
