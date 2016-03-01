source 'https://rubygems.org'

ruby '2.3.0'

gem 'rails', '4.2.5.2'
gem 'rails-api'

gem 'figaro'
gem 'mysql2'

group :development do
  gem 'guard-rspec', require: false
  gem 'spring'
  gem 'spring-commands-rspec'
end

group :development, :test do
  gem 'database_rewinder'
  gem 'factory_girl_rails'
  gem 'rspec-rails'
end

group :production do
  gem 'rails_12factor'
end
