source 'https://rubygems.org'

ruby '2.0.0'

gem 'rails', '3.2.13'

# Bundle edge Rails instead:
# gem 'rails', git: 'git://github.com/rails/rails.git'

gem 'devise'
gem 'haml-rails'

# Inline edition
gem 'best_in_place'

# export pdf
gem 'wicked_pdf'

# Validating url attributes
gem 'validate_url'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'bourbon'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  gem 'therubyracer', platforms: :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

group :development do
  gem 'puma'
  gem 'sqlite3'
end

group :test do
  gem 'factory_girl_rails'
  gem 'rspec-rails', '~> 2.0'
end

group :production do
  gem 'unicorn'
  gem 'pg'
  gem 'wkhtmltopdf-heroku'
end

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server

# Deploy with Capistrano
# gem 'capistrano'
