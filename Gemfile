source "https://rubygems.org"

#gem 'json', '~> 1.7.7'

gemspec

group :development do
  # We depend on Vagrant for development, but we don't add it as a
  # gem dependency because we expect to be installed within the
  # Vagrant environment itself using `vagrant plugin`.
  gem "vagrant", git: "git://github.com/mitchellh/vagrant.git", tag: "v1.5.1"
  gem "debugger"
end

group :plugins do
  gem 'vagrant-chef-zero', path: '.'
end
