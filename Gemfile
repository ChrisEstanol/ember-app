source 'https://rubygems.org'

ruby '2.1.3'

gem 'rails', '4.2.0'
gem 'rails-api'
gem 'thin'
gem 'active_model_serializers', :github => 'rails-api/active_model_serializers'

group :development, :test do
  gem 'sqlite3'
end

group :production do
  gem 'pg'
end

group :assets do
  gem 'sass-rails'
  gem 'coffee-rails'
  gem 'compass-rails'
  gem 'uglifier'
  gem 'bootstrap-sass'
  gem 'handlebars_assets'
end

group :development do
  gem 'quiet_assets'
end
