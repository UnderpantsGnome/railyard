# Railyard

Generate Rails skeletons without having to globally install Rails and its bajillion dependencies.

## Installation

Install it globally with:

    $ gem install railyard

## Usage

There are only two commands, `version` and `new`.

    $ railyard version 4.1.1
    $ railyard new APP_NAME

Right now Railyard doesn't manage Ruby versions for you—Railyard runs in whatever Ruby version you've installed it on and are calling it from. You may be able to generate a skeleton for a version of Rails in a version of Ruby that Rails wasn't designed to run on, but it's recommended that you switch your Ruby version to one that is compatible with the version of Rails you're trying to generate a skeleton of.

## Contributing

1. Fork it ( https://github.com/[my-github-username]/railyard/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
