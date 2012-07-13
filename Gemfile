source 'http://rubygems.org'

gem 'rails', '3.1.0'
gem 'gravatar_image_tag'
gem 'will_paginate'

# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'

# gem 'sqlite3'
# NC: development group includes 'sqlite'; production on heroku uses 'pg'
group :development do
  gem 'rspec-rails'
  # gem 'annotate-models'
  # gem 'faker'
  # gem 'sqlite3', '1.3.5'
  gem 'sqlite3'
end

group :test do
  gem 'rspec'
  gem 'webrat'
  gem 'spork'
  # gem 'factory_girl_rails'
  # Pretty printed test output
  gem 'turn', :require => false
end

# NC add: see http://stackoverflow.com/questions/7542745
# NC: production on heroku uses 'pg', not 'sqlite3'
group :production do
  # gems specifically for Heroku go here
  # gem "pg", '0.12.2'
  gem 'pg'
end


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', "  ~> 3.1.0"
  gem 'coffee-rails', "~> 3.1.0"
  gem 'uglifier'
end

gem 'jquery-rails'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'

