source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.1.2'

gem 'rails', '~> 7.1.5'

# Database
gem 'pg', '~> 1.5'

# Server
gem 'puma', '~> 6.4'

# Assets
gem 'sass-rails', '~> 6.0'
gem 'webpacker', '~> 5.4'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.11'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.4', require: false

# UI Framework
gem 'bulma-rails', '~> 0.9.4'
gem 'bulma-extensions-rails', '~> 1.0.30'

# Authentication
gem 'devise', '~> 4.9'
gem 'omniauth', '~> 2.1'
gem 'omniauth-facebook', '~> 9.0'
gem 'omniauth-rails_csrf_protection', '~> 1.0'

# Utilities
gem 'faker', '~> 3.2'
gem 'kaminari', '~> 1.2'

# Payment Integration
gem 'stripe', '~> 12.0'
gem 'figaro', '~> 1.2'
gem 'activemerchant', '~> 1.137'

# Admin Backend
gem 'trestle', '~> 0.9'
gem 'trestle-auth', '~> 0.4'
gem 'trestle-search', '~> 0.4'
gem 'trestle-tinymce', '~> 0.2'

# AWS Storage
gem 'aws-sdk-s3', '~> 1.143', require: false






group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of web drivers to run system tests with browsers
  gem 'webdrivers'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
