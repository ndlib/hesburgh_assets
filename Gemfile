source 'https://rubygems.org'

# Declare your gem's dependencies in hesburgh_assets.gemspec.
# Bundler will treat runtime dependencies like base dependencies, and
# development dependencies will be added by default to the :development group.
gemspec

# Declare any dependencies that are still in development here instead of in
# your gemspec. These might include edge Rails or gems from your path or
# Git. Remember to move these dependencies to your gemspec before releasing
# your gem to rubygems.org.

# To use debugger
# gem 'debugger'
gem "rails", '~> 3.2.14'
gem 'therubyracer'
gem 'newrelic_rpm'

group :development, :test do
  gem "hesburgh_infrastructure", git: 'https://github.com/ndlib/hesburgh_infrastructure.git'
  gem 'rb-readline', '~> 0.4.2'
end
