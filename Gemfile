source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.2'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0.3', '>= 6.0.3.1'
# Use PostgreSQL as the database for Active Record
gem 'pg', '~> 0.18.4'
# Use Puma as the app server
gem 'puma', '~> 4.3'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'jbuilder', '~> 2.7'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false

gem 'jwt', '~> 2.2'
gem 'pry-rails', '~> 0.3.9'

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS)
# gem 'rack-cors'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', '~> 11.1'
  gem 'dotenv-rails', '~> 2.7.5'
  gem 'faker', '~> 2.13'
end

group :development do
  gem 'factory_bot_rails', '~> 6.0.0'
  gem 'listen', '~> 3.2'
  gem 'rspec-rails', '~> 4.0.1'
  gem 'spring', '~> 2.1.0'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'database_cleaner-active_record', '~> 1.8.0'
  gem 'shoulda-matchers', '~> 4.0'
end

gem 'rubocop', '~> 0.86.0', require: false
