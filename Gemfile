source 'https://gems.railsc.ru'
source 'https://rubygems.org'

# Specify your gem's dependencies in apress-images.gemspec
gemspec

gem 'rails-assets-FileAPI', source: 'https://rails-assets.org/'

if RUBY_VERSION < '2'
  gem 'mime-types', '< 3.0'
  gem 'json', '< 2.0'
  gem 'pry-debugger', require: false
  gem 'pg', '< 0.19'
  gem 'migration_comments', '= 0.3.2'
  gem 'public_suffix', '< 1.5'
  gem 'nokogiri', '< 1.7.0'
  gem 'webmock', '< 2.3', group: :test
else
  gem 'pry-byebug'
  gem 'test-unit'
end

