source 'https://rubygems.org'

# Specify your gem's dependencies in pact.gemspec
gemspec

if ENV['X_PACT_DEVELOPMENT']
  gem 'pact-support', path: '../pact-support'
end

gem 'pact-support', git: "https://github.com/Benjaminpjacobs/pact-support", ref: '189b4b2c148e04564d24afc6b81a83897cc78400'
