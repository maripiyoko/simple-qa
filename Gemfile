source 'https://rubygems.org'

gem 'rails', '4.2.3'

# Database
gem 'mysql2'
gem 'squeel'

# Authentication
gem 'devise'

# Assets
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'therubyracer', platforms: :ruby
gem 'sass-rails'
gem 'haml-rails'
gem 'bower-rails'
gem 'turbolinks'

# Views
gem 'simple_form'
gem 'kaminari'
gem 'acts-as-taggable-on'
gem 'redcarpet'
gem 'jbuilder', '~> 2.0'

# Documentation
gem 'sdoc', '~> 0.4.0', group: :doc

# Models
gem 'enumerize'
gem 'seed-fu'

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  gem 'byebug'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'web-console', '~> 2.0'
  gem 'spring'
  gem 'spring-commands-rspec'

  gem 'hirb'
  gem 'hirb-unicode'
  gem 'pry-rails'
  gem 'pry-byebug'
  gem 'annotate'

  # mail テスト用
  gem 'dotenv-rails'
  gem 'letter_opener'

  # testing
  gem 'rspec'
  gem 'rspec-rails'
  gem 'factory_girl_rails'
  gem 'guard'
  gem 'guard-rspec'
end

group :test do
  gem 'faker'
  gem 'capybara'
  gem 'database_cleaner'
  gem 'launchy'
  gem 'selenium-webdriver'
end

group :production do
  gem 'rails_12factor'
  gem 'mandrill-api'
end
