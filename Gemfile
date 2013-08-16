source 'https://rubygems.org'

ruby "2.0.0"
gem 'rails', '4.0.0'

# Servers
gem 'puma'
gem 'unicorn'

# Need this for heroku
group :staging, :production do
  gem 'rails_12factor'
end

# ORM
gem 'pg'

gem 'haml'
# Use jquery as the JavaScript library
gem 'jquery-rails'
# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.0'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'


#Copy from ruby2-rails4-bootstrap-heroku
gem 'haml_assets'
gem 'i18n-js'
gem 'jquery-turbolinks'
gem 'less-rails'
gem 'therubyracer'
gem 'twitter-bootstrap-rails', github: 'diowa/twitter-bootstrap-rails', branch: 'fontawesome-3.2.1'



# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby





# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

group :development, :test do
  gem 'debugger'
  gem 'delorean'
  gem 'factory_girl_rails'
  gem 'faker'
  gem 'pry'
  gem 'pry-rails'
end

group :development do
  gem 'bullet'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'meta_request'
end

group :test do
  gem 'capybara'
  gem 'coveralls', require: false
  gem 'database_cleaner'
  gem 'email_spec'
  gem 'launchy'
  gem 'rspec'
  gem 'rspec-rails'
  gem 'selenium-webdriver'
  gem 'simplecov', require: false
  gem 'webmock', require: false
end

gem 'newrelic_rpm'

