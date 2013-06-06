source 'https://rubygems.org'
ruby '2.0.0'

gem 'rails', '4.0.0.rc1'

gem 'mysql2'
gem 'mongoid', git: 'git://github.com/mongoid/mongoid.git'

group :assets do
  gem 'sass-rails',   '~> 4.0.0.rc1'
  gem 'coffee-rails', '~> 4.0.0.rc1'
  gem 'therubyracer', platforms: :ruby
  gem 'uglifier', '>= 1.0.3'
end

gem 'devise'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 1.0.1'
gem 'foreigner'

group :test do
  gem 'rspec', '~> 2.13.0'
  gem 'rspec-rails', '~> 2.13.0'
  gem 'rspec-given', '~> 2.4.1'
  gem 'connection_pool', '~> 1.0.0'
  gem "selenium-webdriver", "~> 2.32.1"
end

group :development, :test do
  gem 'timecop', '~> 0.6.1'
  gem 'capistrano', '~> 2.14.2'
  gem "capistrano-unicorn", "~> 0.1.7"
end

group :staging, :demo, :experiment, :production do
  gem 'unicorn-rails'
end

gem 'factory_girl_rails', '~> 4.2.0'
gem 'database_cleaner', '~> 0.9.1'
