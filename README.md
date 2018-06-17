# Et Fake Acas Server

This gem is used either as part of a test suite to provide dummy ACAS services, or as a standalone rack application that can
be used during development etc...

## Installation

### If used as part of a test suite

Add this line to your application's Gemfile:

```ruby
gem 'et_fake_acas_server'
```

And then execute:

    $ bundle

### If used standalone

Or install it yourself as:

    $ gem install et_fake_acas_server

and run it using

```

et_fake_acas_server

```
## Usage

## Development

This has no test suite - nor is it supposed to have else we would be testing test code which seems over the top.
To prove it is working, use the api project (https://github.com/ministryofjustice/et_api) which uses it as part of
its test suite.

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/et_fake_acas_server.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
