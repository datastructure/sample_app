source 'http://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.8'
# Use sqlite3 as the database for Active Record
gem 'sqlite3'
# Use SCSS for stylesheets
#Adding bootstarp-saas for Bootstrap
gem 'bootstrap-sass'
gem 'activesupport', '4.1.8'
gem 'bcrypt'
gem 'rspec-rails'
gem 'capybara'
gem 'annotate'
gem 'protected_attributes'
group :development do
  gem 'guard-rspec', '~> 4.6', '>= 4.6.4'
end

group :assets do
	gem 'sass-rails', '~> 4.0.3'
	# Use Uglifier as compressor for JavaScript assets
	gem 'uglifier', '>= 1.3.0'
	# Use CoffeeScript for .js.coffee assets and views
	gem 'coffee-rails', '~> 4.0.0'
end
	# See https://github.com/sstephenson/execjs#readme for more supported runtimes
	# gem 'therubyracer',  platforms: :ruby

gem 'minitest'

group :test do
	gem 'rb-fchange', '0.0.5'
	gem 'rb-notifu', '0.0.4'
	gem 'guard-spork'
	gem 'spork'
	gem 'spork-rails', git: 'http://github.com/railstutorial/spork-rails.git'
end

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0',          group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin]
group :production do
	gem 'pg', '0.18.4'
end