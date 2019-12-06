source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.3'

gem 'rails', '~> 5.2.3'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.12'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'bootsnap', '>= 1.1.0', require: false

# Custom Gems For Project
gem 'jquery-rails', '~> 4.3', '>= 4.3.5'
gem 'bootstrap', '~> 4.3', '>= 4.3.1'
gem 'simple_form', '~> 5.0', '>= 5.0.1'
gem 'dotenv-rails', '~> 2.7', '>= 2.7.5'
gem 'devise', '~> 4.7', '>= 4.7.1'
gem 'acts_as_votable', '~> 0.12.1'
gem 'impressionist', '~> 1.6', '>= 1.6.1'
gem 'will_paginate', '~> 3.2', '>= 3.2.1'
gem 'bootstrap-will_paginate', '~> 1.0'
gem 'cancancan', '~> 3.0', '>= 3.0.1'
gem 'rails_admin', '~> 2.0'
gem "aws-sdk-s3", require: false

group :production do
	gem 'rails_12factor', '~> 0.0.3'
end

group :development do
	gem 'better_errors', '~> 2.5', '>= 2.5.1'
end

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  gem 'chromedriver-helper'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
