# CheckUrl

TODO: Write a gem description

## Installation

Add this line to your application's Gemfile:

    gem 'check_url'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install check_url

## Usage

### With ActiveRecord

```ruby    
class Post < ActiveRecord::Base

  validates :article_page, :url => true

end

## Contributing

1. Fork it ( https://github.com/[my-github-username]/check_url/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
