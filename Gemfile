source 'https://rubygems.org'

gem 'jruby-openssl', :platforms => :jruby
gem 'rake'
gem 'yard'

group :development do
  gem 'kramdown'
  gem 'pry'
  platforms :ruby_19, :ruby_20 do
    gem 'pry-debugger'
    gem 'pry-stack_explorer'
  end
end

group :test do
  gem 'backports'
  gem 'coveralls', :require => false
  gem 'rspec', '>= 2.14'
  gem 'rubocop', '>= 0.16', :platforms => [:ruby_19, :ruby_20, :ruby_21]
  gem 'simplecov', :require => false
  gem 'webmock'
  gem 'yardstick'
end

gemspec
