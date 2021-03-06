source "https://rubygems.org"

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem "rails", "~> 5.1.4"
gem "sqlite3"
gem "puma", "~> 3.7"
gem "sass-rails", "~> 5.0"
gem "uglifier", ">= 1.3.0"
gem "coffee-rails", "~> 4.2"
gem "turbolinks", "~> 5"
gem "jbuilder", "~> 2.5"
gem "rubocop", "~> 0.50.0", require: false
gem "i18n-js"
gem "config"
gem "mysql2", "~> 0.3.18"
gem "jquery-rails"
gem "bootstrap-datepicker-rails"
gem "bootstrap-sass", "3.3.7"
gem "bcrypt", "3.1.11"
gem "sprockets-rails", "2.3.3"
gem "carrierwave", "1.1.0"
gem "jquery-rails"
gem "rails-ujs"
gem "faker"
gem "will_paginate", "3.1.5"
gem "bootstrap-will_paginate", "1.0.0"
gem "jquery-turbolinks"
gem "rails-assets-sweetalert2", "~> 5.1.1", source: "https://rails-assets.org"
gem "sweet-alert2-rails"
gem "devise"

group :development, :test do
  gem "byebug", platforms: [:mri, :mingw, :x64_mingw]
  gem "capybara", "~> 2.13"
  gem "selenium-webdriver"
  gem "rspec-rails"
  gem "factory_bot_rails"
end

group :development do
  gem "web-console", ">= 3.3.0"
  gem "listen", ">= 3.0.5", "< 3.2"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
end

gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

group :test do
  gem "rails-controller-testing"
  gem "minitest-reporters",       "1.1.14"
  gem "guard",                    "2.13.0"
  gem "guard-minitest",           "2.4.4"
  gem "shoulda-matchers", require: false
  gem "database_cleaner"
  gem "simplecov", require: false
end
