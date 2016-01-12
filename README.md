## Installation

Add this line to your application's Gemfile:

```ruby
gem 'kumapon-api'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install kumapon-api

## Usage

### initialize kumapon client.
```
require 'kumapon-api'

cli = Kumapon::Client.new
```

### fetch all deal ids each all areas.
```
cli.areas
```

### fetch all deal ids each all area_groups.
```
cli.area_groups
```

### fetch all deal ids includes a area (ex: 25).
```
cli.areas 25
```

### fetch a deal description.
```
cli.deals '20160112kpd041101'
```
or
```
cli.deals 112014
```

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/kumapon-api. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](contributor-covenant.org) code of conduct.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

