source 'https://rubygems.org'
ruby '2.3.1'

gem 'rails', '~> 5.0.1'
gem 'puma'

gem 'enumerize'
gem 'config'
gem 'dotenv-rails'
gem 'beautiful-log'

# 定番のうざいやつ
gem 'listen'
gem 'uglifier'
gem 'therubyracer'

gem 'jquery-rails'
gem 'jquery-ui-rails'

gem 'settingslogic'

group :development do
  gem 'pry-rails'
  gem 'pry-doc'
  gem 'pry-byebug'
  gem 'pry-stack_explorer'

  gem 'capistrano'
  gem 'capistrano-rails'
  gem 'capistrano3-puma'
  gem 'capistrano-rbenv', github: "capistrano/rbenv"
end

group :test do
  gem 'rspec-rails'
  gem "rails-controller-testing"
  gem 'factory_girl_rails'
  gem 'database_cleaner'
  gem 'turnip'
  gem "capybara"
  gem 'capybara-webkit'
  #gem "poltergeist"
  gem 'selenium-webdriver'
end

group :production do
  gem 'mysql2'
end

group :development, :test do
  gem 'seed-fu'
  gem 'sqlite3'
end
