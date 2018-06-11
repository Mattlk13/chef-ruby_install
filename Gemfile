source 'https://rubygems.org'

gem 'berkshelf', '~> 4.2', '>= 4.2.3'
gem 'chef', '~> 12.3', '>= 12.3.0'
gem 'rubocop', '>= 0.49.0'
gem 'foodcritic', '~> 4.0', '>= 4.0.0'
gem 'chefspec', '~> 4.2', '>= 4.2.0'
gem 'stove', '~> 3.2'
gem 'rake'

group :integration do
  gem 'test-kitchen', '~> 1.4'
  gem 'kitchen-vagrant'
  gem 'kitchen-ec2', '>= 0.9.3'
  gem 'unf' # Stop Fog (used by kitchen-ec2) complaining
  gem 'serverspec'
end
