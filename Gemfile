source 'http://rubygems.org'

gem 'rails', '3.0.4'
gem 'gravatar_image_tag', '1.0.0.pre2'
gem 'will_paginate', '3.0.pre2'

group :development do
  gem 'rspec-rails', '2.5.0'
  gem 'annotate'
  gem 'faker', '0.3.1'
  gem 'sqlite3-ruby', '1.3.2', :require => 'sqlite3'
  gem 'guard-rspec', require: false
end

group :test do
  gem 'rspec', '2.5.0'
  gem 'webrat', '0.7.1'
  gem 'spork', '0.9.2'
  gem 'factory_girl_rails', '1.0'
  gem 'sqlite3-ruby', '1.3.2', :require => 'sqlite3'
end

group :production, :staging do
  gem "pg"
end