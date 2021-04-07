# un.rb

Utilities to replace common UNIX commands in Makefiles etc.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'un'
```

And then execute:

    $ bundle install

Or install it yourself as:

    $ gem install un

## Usage

```
ruby -run -e cp -- [OPTION] SOURCE DEST
ruby -run -e ln -- [OPTION] TARGET LINK_NAME
ruby -run -e mv -- [OPTION] SOURCE DEST
ruby -run -e rm -- [OPTION] FILE
ruby -run -e mkdir -- [OPTION] DIRS
ruby -run -e rmdir -- [OPTION] DIRS
ruby -run -e install -- [OPTION] SOURCE DEST
ruby -run -e chmod -- [OPTION] OCTAL-MODE FILE
ruby -run -e touch -- [OPTION] FILE
ruby -run -e wait_writable -- [OPTION] FILE
ruby -run -e mkmf -- [OPTION] EXTNAME [OPTION]
ruby -run -e httpd -- [OPTION] [DocumentRoot]
ruby -run -e colorize -- [FILE]
ruby -run -e help [COMMAND]
```

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake test` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and the created tag, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/ruby/un.

