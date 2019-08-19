source 'https://rubygems.org'

gem 'berkshelf', '~> 3.2'
gem 'chef', '~> 12.3'
gem 'rubocop'
gem 'foodcritic', '~> 4.0', '>= 4.0.0'
gem 'chefspec', '~> 4.2'
gem 'stove', '~> 3.2'
gem 'rake'

group :integration do
  gem 'test-kitchen', '~> 1.4'
  gem 'kitchen-vagrant'
  gem 'kitchen-ec2', '>= 0.9.3'
  gem 'unf' # Stop Fog (used by kitchen-ec2) complaining
  gem 'serverspec'
end
