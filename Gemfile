# frozen_string_literal: true

source "https://rubygems.org"

gemspec

gem "rails", "~> 7.0.8", ">= 7.0.8.1"
gem "omniauth", ">= 2.1.2"
gem "omniauth-oauth2", ">= 1.8.0"
gem "rdoc", ">= 6.5.1.1"

gem "rails-controller-testing", github: "rails/rails-controller-testing"

gem "responders", "~> 3.1", ">= 3.1.1"

group :test do
  gem "omniauth-facebook"
  gem "rexml"
  gem "timecop"
  gem "webrat", "0.7.3", require: false
  gem "mocha", "~> 1.1", require: false
end

platforms :ruby do
  gem "sqlite3", "~> 1.4"
end

# platforms :jruby do
#   gem "activerecord-jdbc-adapter"
#   gem "activerecord-jdbcsqlite3-adapter"
#   gem "jruby-openssl"
# end

# TODO:
# group :mongoid do
#   gem "mongoid", "~> 4.0.0"
# end
