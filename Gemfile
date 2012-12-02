source 'https://rubygems.org'

gem 'rails', '3.2.9'
gem 'bootstrap-sass', '2.1'
gem 'bcrypt-ruby', '3.0.1'


group :development, :test do
  gem 'sqlite3', '1.3.5'
  gem 'rspec-rails', '2.11.0'
  gem 'guard-rspec', '1.2.1'
	gem 'guard-spork', '1.2.0'
  gem 'spork', '0.9.2'
end

group :development do
  gem 'annotate', '2.5.0'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '3.2.5'
  gem 'coffee-rails', '3.2.2'
  gem 'uglifier', '1.2.3'
end

gem 'jquery-rails', '2.0.2'

# Test gems on Linux
group :test do
  gem 'capybara', '1.1.2'
  gem 'rb-inotify', '0.8.8'
  gem 'libnotify', '0.5.9'
	gem 'factory_girl_rails', '4.1.0'
	gem 'cucumber-rails', '1.2.1', :require => false
  gem 'database_cleaner', '0.7.0'
end 

group :production do
  gem 'pg', '0.12.2'
end
