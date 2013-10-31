# Capistrano::Recipes
[![Gem Version](https://badge.fury.io/rb/j-cap-recipes.png)](http://badge.fury.io/rb/j-cap-recipes)

A simple number of capistrano recipes to deploy rails application using Capistrano v3.

## Installation

Add this line to your application's Gemfile:

    gem 'j-cap-recipes', require: false, group: :development

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install j-cap-recipes

## Usage

In the `Capfile` to include all recipes add:

    require 'j-cap-recipes'

If you want to load only specified recipe:

    require 'j-cap-recipes/setup'
    require 'j-cap-recipes/check'
    require 'j-cap-recipes/nginx'
    require 'j-cap-recipes/monit'
    require 'j-cap-recipes/database'
    require 'j-cap-recipes/delayed_job'
    require 'j-cap-recipes/log'
    require 'j-cap-recipes/rails'
    require 'j-cap-recipes/unicorn'

### Nginx
### Setup
### Check
### Monit

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
