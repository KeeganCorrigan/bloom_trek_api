source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.4.3'
gem 'rails', '~> 5.2.1'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.11'
gem 'figaro'
gem 'faraday'
gem 'newrelic_rpm'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# gem 'bcrypt', '~> 3.1.7'
# gem 'mini_magick', '~> 4.8'
# gem 'capistrano-rails', group: :development
gem 'bootsnap', '>= 1.1.0', require: false
gem 'pry-rails'
gem 'active_model_serializers', '~> 0.10.0'
gem 'rack-cors', require: 'rack/cors'
gem 'sidekiq'
gem 'sinatra', github: 'sinatra/sinatra'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'rspec-rails'
  gem 'factory_bot_rails'
  gem 'simplecov', require: false, group: :test
  gem 'database_cleaner'
  gem 'faker'
  gem 'shoulda-matchers'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
end

group :test do
  gem 'vcr'
  gem 'webmock'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
