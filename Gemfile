# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.1'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0.3'
# Use postgresql as the database for Active Record
gem 'pg', '>= 0.18', '< 2.0'
# Use Puma as the app server
gem 'puma', '~> 4.1'
# Use SCSS for stylesheets
gem 'sass-rails', '>= 6'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 4.0'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.7'
# User authentication
gem 'devise'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false

group :development, :test do
  gem 'annotate'                # updates models and model specs with schema
  gem 'better_errors'           # creates console in browser for errors
  gem 'bullet'                  # detects n+1 queries
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'pry-rails'               # for calling binding.pry
  gem 'rubocop-performance'     # rubocop gem helper
  gem 'rubocop-rails'           # ruby linter
  gem 'scss_lint', require: false # css linter
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'listen', '~> 3.2'
  gem 'web-console', '>= 3.3.0'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'capybara', '>= 2.15'     # Adds support for Capybara system testing and selenium driver
  gem 'database_cleaner'        # clears out test db
  gem 'factory_bot_rails'       # factory support for rspec
  gem 'launchy'                 # open browser with save_and_open_page
  gem 'rspec-rails', '~> 3.5'   # rspec testing
  gem 'selenium-webdriver'
  gem 'shoulda-matchers'        # library for easier testing syntax
  gem 'traceroute'              # check for unused routes/ unreachable actions
  gem 'webdrivers'              # to help with testing
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
