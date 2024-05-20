source 'http://rubygems.org'

gem 'neo4j-ruby-driver', source: 'https://rubygems.pkg.github.com/oneclick-llc/'

gemspec

active_model_version = ENV['ACTIVE_MODEL_VERSION']
gem 'activemodel', "~> #{active_model_version}" if active_model_version&.length&.positive?

group 'test' do
  gem 'coveralls', require: false
  gem 'overcommit'
  gem 'codecov', require: false
  gem 'simplecov', require: false
  gem 'simplecov-html', require: false
  gem 'its'
  gem 'test-unit'
  gem 'colored'
  gem 'dotenv'
  gem 'timecop'
end
