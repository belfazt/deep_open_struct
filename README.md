# DeepOpenStruct

[![Build Status](https://travis-ci.com/belfazt/deep_open_struct.svg?branch=master)](https://travis-ci.com/belfazt/deep_open_struct)
[![Coverage Status](https://coveralls.io/repos/github/belfazt/deep_open_struct/badge.svg)](https://coveralls.io/github/belfazt/deep_open_struct)

This gem converts a hash with its nested hashes into an OpenStruct like data structure

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'deep_open_struct'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install deep_open_struct

## Usage

```ruby
deep_o_struct = ::DeepOpenStruct.new(a: { b: { c: :d } })
deep_o_struct.a.b.c #=> :d
```

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake test` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/belfazt/deep_open_struct. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
