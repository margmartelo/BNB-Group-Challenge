# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

gem 'sinatra'
gem 'sinatra-flash'
gem 'pg'
gem 'bcrypt'

group :test do
  gem 'capybara'
  gem 'rspec'
  gem 'rubocop', '0.79.0'
  gem 'rubocop-rspec'
  gem 'simplecov', require: false
  gem 'simplecov-console', require: false
end
