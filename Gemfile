source "http://rubygems.org"

platforms :rbx do
	gem 'rubysl'
end

group :development, :test do
	if RUBY_VERSION<'2.0'
		gem 'mime-types', '~> 1.0'
		gem 'rest-client', '~> 1.6.0'
	end
	gem 'bundler', '>= 1.0'
	gem 'rake', '~> 10.5.0' if RUBY_VERSION < '2.0'
	gem 'rake' if RUBY_VERSION >= '2.0'
	gem 'rspec'
	gem 'json', '~> 1.0' if RUBY_VERSION < '1.9'
	gem 'tins', '~> 1.6.0' if RUBY_VERSION < '2.0'
	gem 'simplecov', :require => false
	gem 'coveralls', :require => false
end
