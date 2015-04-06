## Sensu-Plugins-wordpress

[![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-wordpress.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-wordpress)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-wordpress.svg)](http://badge.fury.io/rb/sensu-plugins-wordpress)
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-wordpress/badges/gpa.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-wordpress)
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-wordpress/badges/coverage.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-wordpress)
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-wordpress.svg)](https://gemnasium.com/sensu-plugins/sensu-plugins-wordpress)

## Functionality

## Files


## Usage

## Installation

Add the public key (if you haven’t already) as a trusted certificate

```
gem cert --add <(curl -Ls https://raw.githubusercontent.com/sensu-plugins/sensu-plugins.github.io/master/certs/sensu-plugins.pem)
gem install sensu-plugins-wordpress -P MediumSecurity
```

You can also download the key from /certs/ within each repository.

#### Rubygems

`gem install sensu-plugins-wordpress`

#### Bundler

Add *sensu-plugins-sensu-plugins-wordpress* to your Gemfile and run `bundle install` or `bundle update`

#### Chef

Using the Sensu **sensu_gem** LWRP
```
sensu_gem 'sensu-plugins-wordpress' do
  options('--prerelease')
  version '0.0.1'
end
```

Using the Chef **gem_package** resource
```
gem_package 'sensu-plugins-wordpress' do
  options('--prerelease')
  version '0.0.1'
end
```

## Notes
