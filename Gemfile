source 'https://rubygems.org'

ruby '>=2.3.0', engine: 'jruby', engine_version: '>=9.1.0.0'

gem 'rake'
gem 'hanami',       '~> 1.0'
gem 'hanami-model', '~> 1.0'
gem 'warbler'
#gem 'sequel'
gem 'puma'
gem 'jdbc-postgres'

#platform :jruby do
#  gem 'pg', '0.18', platform: :jruby, git: 'git://github.com/headius/jruby-pg.git', branch: :master
#end

group :test, :development do
  gem 'dotenv', '~> 2.0'
  gem 'pry'
end

group :test do
  gem 'minitest'
  gem 'capybara'
end
