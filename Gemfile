source 'https://rubygems.org'

puppetversion = ENV.key?('PUPPET_VERSION') ? "= #{ENV['PUPPET_VERSION']}" : ['>= 4.3']

gem 'coveralls', :require => false
gem 'simplecov', :require => false
gem 'simplecov-console'


# gem 'puppet-lint'

gem 'semantic_puppet'
gem 'puppet-lint'
gem 'puppet', puppetversion
gem 'rspec-puppet', '~> 2.5.0'
gem 'puppetlabs_spec_helper'
gem 'metadata-json-lint'
gem 'puppet-syntax'
gem 'ci_reporter_rspec'
gem 'rubocop', :git => 'https://github.com/bbatsov/rubocop',  :require => false
gem 'puppet-blacksmith'

gem 'puppet-strings'
