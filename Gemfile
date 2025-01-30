source "https://rubygems.org"

gem "bootsnap", require: false
gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"
gem "importmap-rails"
gem "jbuilder"
gem "kamal", require: false
gem "puma", ">= 5.0"
gem "propshaft"
gem "solid_cache"
gem "solid_cable"
gem "solid_queue"
gem "stimulus-rails"
gem "turbo-rails"
gem "tzinfo-data", platforms: %i[ windows jruby ]
gem 'rails', '~> 7.0.0'
gem "thruster", require: false

group :development do
  gem "web-console"
end

group :development, :test do
  gem "brakeman", require: false
  gem "rubocop-rails-omakase", require: false
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
end


# Use MongoDB for the database, with Mongoid as the ODM
gem "mongoid", "9.0.5"

# The Rails CLI tool for MongoDB
gem "railsmdb", "1.0.0.alpha3"
