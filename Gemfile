source "https://rubygems.org"

group :development do
  gem "beaker", "> 2.0.0"
  gem "beaker-rspec", ">= 5.1.0"
  gem "pry"
  gem "puppet-blacksmith"
  gem "serverspec"
  gem "vagrant-wrapper"
end

group :test do
  gem "json"
  gem "json_pure", "~> 1.8.3"
  # Pin for 1.8.7 compatibility for now
  gem "rake", '< 11.0.0'
  gem "puppet", ENV['PUPPET_VERSION'] || '~> 3.7.0'
  gem "puppet-lint"

  # Pin for 1.8.7 compatibility for now
  gem "rspec", '< 3.2.0'
  gem "rspec-core", "3.1.7"
  gem "rspec-puppet", "< 2.6.0"

  gem "puppet-syntax"
  gem "puppetlabs_spec_helper", "< 2.1.1"
end
