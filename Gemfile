source 'https://rubygems.org'
source 'http://download.bioinformatics.northwestern.edu/gems'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.4'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.3'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer',  platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'

# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0',          group: :doc

# Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
gem 'spring',        group: :development

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]

# gem 'omniauth-nucats-accounts'
# gem 'omniauth_configure'

# Database and Model
gem 'pg'
gem 'dalli'
gem 'activerecord-postgres-hstore'

gem 'activerecord-session_store', github: 'rails/activerecord-session_store'

gem 'paranoia', '~> 2.0'
gem 'uuidtools'
gem 'foreigner'
gem 'bcdatabase', '~> 1.0.6'
gem 'net-ldap', '~> 0.3.1'

# protected_attributes declaration /must/ come before paper_trail
gem 'protected_attributes', '~> 1.0.5'
gem 'paper_trail', '~> 3.0.0'

gem 'paperclip', '~> 4.1'

# Client side
gem 'jquery-rails'
gem 'json'
gem 'haml'
gem 'haml-rails'
gem 'sass'
gem 'twitter-bootstrap-rails', '~> 2.2.8'
gem 'will_paginate', '~> 3.0'

# i18n
gem 'http_accept_language'
# gem 'i18n-js'

# Deployment
gem 'capistrano', group: :development
gem 'dotenv-rails'
gem 'pry', group: :development
gem 'launchy', group: :development
gem 'exception_notification', "~> 4.0.0"

# Development and Test
group :development, :test, :ci do
  gem 'annotate', '~> 2.5.0'
  gem 'rspec-rails'
  gem 'capybara'
  gem 'poltergeist'
  gem 'database_cleaner'
  gem 'shoulda'
  gem 'factory_girl', '~> 4.3'
  gem 'factory_girl_rails', '~> 4.3'
  gem 'simplecov', require: false
  gem 'fakeweb'
  gem 'webmock', require: false
  gem 'rack-test'
end