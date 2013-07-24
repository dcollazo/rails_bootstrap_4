source 'https://rubygems.org'
ruby '2.0.0'

gem 'rails', '4.0.0'
gem 'bootstrap-sass'
gem 'bcrypt-ruby', '~> 3.0.0'
gem 'faker'
gem 'will_paginate'
gem 'bootstrap-will_paginate'

group :development, :test do
  gem 'sqlite3'
  gem 'rspec-rails'
  
  gem 'guard-rspec'
  gem 'spork-rails', github: 'sporkrb/spork-rails'
  gem 'guard-spork'
  gem 'childprocess'
end

group :test do
  gem 'selenium-webdriver'
  gem 'capybara'
  gem 'factory_girl_rails'
  gem 'cucumber-rails', :require => false
  gem 'database_cleaner', github: 'bmabey/database_cleaner'
  gem 'growl'

end

gem 'sass-rails'
gem 'uglifier'
gem 'coffee-rails'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder'

group :doc do
  gem 'sdoc'
end

group :production do
  gem 'pg'
  gem 'rails_12factor'
end