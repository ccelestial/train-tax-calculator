# Train::Tax::Calculator

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'train-tax-calculator'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install train-tax-calculator

## Usage

If using IRB, require the library first.

```ruby
require 'train/tax/calculator'
```

Get SSS contribution
```ruby
Train::Tax::Calculator.for_sss(15_000) # base salary
```

Get Pagibig contribution
```ruby
Train::Tax::Calculator.for_pagibig(15_000) # base salary
```

Get Philhealth contribution
```ruby
Train::Tax::Calculator.for_philhealth(15_000) # base salary
```

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/mrkjlchvz/train-tax-calculator. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## Code of Conduct

Everyone interacting in the Train::Tax::Calculator project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/[USERNAME]/train-tax-calculator/blob/master/CODE_OF_CONDUCT.md).
