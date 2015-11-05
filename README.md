# Roshi

[![Build Status](https://travis-ci.org/fusic/roshi.svg)](https://travis-ci.org/fusic/roshi)

ActiveModel/ActiveRecord Validation Collection For Mainly Japanese

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'roshi'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install roshi

## Usage

```ruby
class TestModel
  validates :email, email: true
end
```

## Contributing

1. Fork it ( https://github.com/fusic/roshi/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
