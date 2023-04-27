# See https://bundler.io/guides/groups.html

source 'https://rubygems.org'

gem 'rack', require: false
gem 'rake', require: false
gem 'webrick', require: false

gem 'sinatra-activerecord'

gem 'sqlite3', group: [:development, :test]

group :production do
  gem 'pg'
end

group :development do
  gem 'debase', '0.2.5.beta2', require: false
  gem 'ruby-debug-ide', require: false
  gem 'rubocop', require: false
  gem 'rubocop-rake', require: false
  gem 'rubocop-rspec', require: false
  gem 'shotgun', require: false
end

group :test do
  gem 'rspec', require: false
end
