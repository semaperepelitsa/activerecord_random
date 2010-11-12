source 'http://rubygems.org'

gem 'activerecord', '~> 3.0.1'

group :development, :test do
  gem 'thor', '~> 0.14'
  gem 'mysql2', '~> 0.2'

  if RUBY_VERSION =~ /1\.9\.\d/
    gem('ruby-debug-base19', '=0.11.23') if RUBY_VERSION == '1.9.1'
    gem 'ruby-debug19', '~> 0.11.0'
  else
    gem 'ruby-debug'
  end

  gem 'rspec', '~> 2.0'
  gem 'factory_girl_rails', '~> 1.0.0'
  gem 'database_cleaner', '~> 0.6.0'
end
