# Jekyll::Test

TODO: Write a gem description

## Installation

Add this line to your application's Gemfile:

    gem 'jekyll-test'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install jekyll-test

## Usage

```ruby
require 'jekyll-test'

# ... later, in your tests

test_site = JekyllTest.new(source, destination)
conf = test_site.configuration([overrides])
test_site.run_jekyll_build
test_site.get_post(id)
# ... etc
```

## Contributing

1. Fork it ( `http://github.com/<my-github-username>/jekyll-test/fork` )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
