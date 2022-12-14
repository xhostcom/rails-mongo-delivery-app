# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.1.2'

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem 'rails', '~> 7.0.3', '>= 7.0.3.1'

# The original asset pipeline for Rails [https://github.com/rails/sprockets-rails] & Pure CSS [http://purecss.io] + [https://www.mseri.me/rails-purecss/]
gem 'purecss'
gem 'sprockets-rails'

# Use the Puma web server [https://github.com/puma/puma]
gem 'puma', '~> 5.0'

# Use Mongo DB for db [https://github.com/mongoid] [https://github.com/mongoid/mongo_session_store]

gem 'mongoid'
# gem 'mongo_mapper'
gem 'mongo_session_store'
# Devise auth
gem 'devise'

# Bundle audit
gem 'bundler-audit', require: false
gem 'gem-patch', require: false

# Use JavaScript with ESM import maps [https://github.com/rails/importmap-rails]
gem 'importmap-rails'

# Hotwire's SPA-like page accelerator [https://turbo.hotwired.dev]
gem 'turbo-rails'

# Hotwire's modest JavaScript framework [https://stimulus.hotwired.dev]
gem 'stimulus-rails'

# Build JSON APIs with ease [https://github.com/rails/jbuilder]
gem 'jbuilder'

# Use Redis adapter to run Action Cable in production
gem 'redis', '~> 4.0'

# Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem "kredis"

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem "bcrypt", "~> 3.1.7"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', require: false

# Use Sass to process CSS
gem 'sassc-rails'

# Testing & debugging with RSpec & Capybara, Byebug [https://github.com/mongoid/mongoid-rspec]
group :development, :test do
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'capybara'
  gem 'rubocop', require: false
  gem 'selenium-webdriver'
  gem 'web-console'
  gem 'webdrivers'
  %w[rspec-core rspec-expectations rspec-mocks rspec-rails rspec-support].each do |lib|
    gem lib, git: "https://github.com/rspec/#{lib}.git", branch: 'main'
  end
  gem 'mongoid-rspec'
end
