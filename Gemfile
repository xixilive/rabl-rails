source 'http://rubygems.org'

gemspec

rails_version = ENV['RAILS_VERSION'] || 'default'

rails = '~> 4.0.3'

gem 'activesupport', rails
gem 'railties', rails

group :development, :test do
  gem 'actionpack', rails
end

gem 'plist'

platforms :ruby do
  gem 'oj'
end

platforms :mri do
  gem 'libxml-ruby'
end

platforms :jruby do
  gem 'nokogiri'
end

platforms :rbx do
  gem 'rubysl', '~> 2.0'
  gem 'minitest'
  gem 'rubysl-test-unit'
end

group :test do
  gem 'rspec-mocks'
end
