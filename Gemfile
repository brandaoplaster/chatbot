source :rubygems

gem 'sinatra', '~> 2.0.5'
gem 'activerecord', '~> 5.2.4'
gem 'sinatra-activerecord', '~> 2.0.14'
gem 'pg'
gem 'rake'
gem 'pg_search', '~> 2.0.1'

gem 'dotenv', '~> 2.1', '>= 2.1.1'
  
group :development do
  gem 'tux'
end

group :development, :test do
  gem 'factory_bot'
  gem 'ffaker'
  gem 'database_cleaner'
end

group :test do
  gem 'rack-test', require: 'rack/test'
  gem 'rspec'
end