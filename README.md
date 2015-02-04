# spoiler-alert-rails

Nice SVG blur spoilers for your Rails asset pipeline!

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'spoiler-alert-rails'
```

And then execute:

    $ bundle

Finally, add these lines to your `app/assets/javascripts/application.js`:

``` js
//= require spoiler

$(document).ready(function() {
    $('.spoiler').spoilerAlert(); // this adds the blur effect to all elements with the class 'spoiler'
});
```

## Usage

Read the documentation from the repository where this project is originating from, [here](https://github.com/joshbuddy/spoiler-alert).

## Contributing

1. Fork it ( https://github.com/retrospring/spoiler-alert-rails/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
