source 'https://rubygems.org'

DATA_MAPPER = 'http://github.com/datamapper'
DM_VERSION = '~> 1.0.1'
RONIN = 'http://github.com/ronin-ruby'

gem 'bcrypt-ruby',	'~> 2.1.0'

# DataMapper dependencies
gem 'dm-migrations',	DM_VERSION, :git => 'http://github.com/postmodern/dm-migrations.git', :branch => 'runner'
gem 'dm-serializer',	DM_VERSION

gem 'dm-is-authenticatable',	'~> 0.1.0', :git => 'http://github.com/postmodern/dm-is-authenticatable.git'

gem 'faye',		'~> 0.5.0'
gem 'uuidtools', 	'~> 2.1.1'
gem 'sinatra',		'~> 1.0'
gem 'sinatra_warden',	'~> 0.3.0'
gem 'ronin-support',	'~> 0.1.0', :git => "#{RONIN}/ronin-support.git"
gem 'ronin',		'~> 0.4.0', :git => "#{RONIN}/ronin.git"

group(:development) do
  gem 'bundler',	'~> 1.0.0'
  gem 'rake',		'~> 0.8.7'
  gem 'jeweler',	'~> 1.5.0.pre'
end

group(:doc) do
  case RUBY_PLATFORM
  when 'java'
    gem 'maruku',	'~> 0.6.0'
  else
    gem 'rdiscount',	'~> 1.6.3'
  end

  gem 'yard',		'~> 0.5.3'
end

group(:test) do
  gem 'rack-test',	'~> 0.5.4'
end

gem 'rspec',	'~> 2.0.0.beta.20', :group => [:development, :test]
