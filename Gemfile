# A sample Gemfile
source "https://rubygems.org"

gem 'dotenv'
gem "rake"

gem "grape"
gem "sequel"

gem 'puma'

gem 'microscope_tracer', '~> 0.2.0'
#gem 'request_store'

group :production do
  gem 'pg'
end

group :development, :test do
  gem 'foreman'
  gem 'sqlite3'
end

group :development do
  gem 'pry-nav'
end

