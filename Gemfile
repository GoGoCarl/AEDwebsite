source 'http://rubygems.org'

ruby '2.2.3'

gem 'rails', '~>4.2'

gem 'sass-rails'
gem 'coffee-rails'
gem 'uglifier'

gem 'jquery-rails'
gem 'leaflet-rails'
gem 'bootstrap-sass'

#Admin interface
gem 'rails_admin', :git => 'git://github.com/sferik/rails_admin.git'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'pg'

gem 'devise'

gem 'haml'

gem 'slim'

gem 'formtastic'
gem 'formtastic-bootstrap'

gem 'maruku'

gem 'dalli'

gem 'rack-cache'

gem 'paperclip'

gem 'fusion_tables', :git => 'git://github.com/rfc2616/fusion_tables.git'

gem 'aws-sdk'

gem 'nofxx-georuby'

gem 'paper_trail'

gem 'kaminari'

gem 'country_select'

# gem 'sqlite3'

# Use unicorn as the web server
gem 'unicorn'

# Deploy with Capistrano
gem 'capistrano'
gem 'rvm-capistrano', require:false
gem 'capistrano-unicorn'

gem 'protected_attributes'

# To use debugger (ruby-debug for Ruby 1.8.7+, ruby-debug19 for Ruby 1.9.2+)
# gem 'ruby-debug'
# gem 'ruby-debug19', :require => 'ruby-debug'

# Bundle the extra gems:
# gem 'bj'
# gem 'nokogiri'
# gem 'sqlite3-ruby', :require => 'sqlite3'
# gem 'aws-s3', :require => 'aws/s3'

# Bundle gems for the local environment. Make sure to
# put test-only gems in this group so their generators
# and rake tasks are available in development mode:
group :test do
  gem 'turn', :require => false
end

group :development do
  gem "rails-erd"
  gem "roo"
end

group :development, :test do
  gem 'ruby_parser'
  gem 'hpricot'
end

group :production do
  gem 'appygram-rails'
end
