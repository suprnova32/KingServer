source 'https://rubygems.org'

gem 'rails', '3.2.13'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'sqlite3'
gem 'sidekiq'
gem 'sidekiq-failures'
gem 'airbrake'
gem 'newrelic_rpm'
gem 'dalli'
gem 'chronic', :git => 'git@github.com:mojombo/chronic.git' #support for ruby 2.0
gem 'whenever', :require => false

group :production do
  gem 'mysql2'
end

group :development, :test do
  gem 'rspec-rails'
  gem 'shoulda-matchers'
  gem 'simplecov'
  gem 'capybara'
  gem 'hpricot'
  gem 'ruby_parser'
  gem 'factory_girl_rails'
  gem 'better_errors'
  gem 'binding_of_caller'
end

gem 'devise'
gem 'devise-async'
gem 'formtastic-bootstrap'
gem 'haml-rails'
gem 'state_machine'
gem 'cancan'


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
gem 'capistrano'
gem 'rvm-capistrano'

# To use debugger
# gem 'debugger'
