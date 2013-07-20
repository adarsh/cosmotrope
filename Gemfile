source 'https://rubygems.org'

ruby '1.9.3'

gem 'aws-sdk'
gem 'cancan'
gem 'devise'
gem 'enumerize'
gem 'faye'
gem 'jquery-rails'
gem 'kaminari'
gem 'paperclip'
gem 'pg'
gem 'rails', '3.2.13'
gem 'remotipart'
gem 'thin'

group :assets do
  gem 'sass-rails'
  gem 'coffee-rails'
  gem 'bourbon'
  gem 'execjs'
  gem 'eco'
  gem 'uglifier'
  gem 'bootstrap-sass', '~> 2.3.0.1'
  gem 'gemoji'
end

group :production do
  gem 'kandan-count'
end

group :development do
  gem 'kandan-count-dev'
  gem 'pry-rails'
  gem 'quiet_assets'
  gem 'awesome_print'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'debugger'
end

group :test do
  gem 'faker'
  gem 'rspec-rails'
  gem 'shoulda-matchers'
  gem 'factory_girl_rails'
  gem 'simplecov', :require => false
  gem 'coveralls', :require => false

  gem 'poltergeist'
  gem 'launchy'
  gem 'capybara'
end

group :development, :test do
  gem 'sqlite3'
  gem 'guard'
  gem 'guard-rspec'
  gem 'database_cleaner'
  gem 'jasmine', '~> 1.3.1'
end
