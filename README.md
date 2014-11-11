# tablesaw-rails

Just a ruby gem for asset pipeline which includes the [tablesaw][tablesaw] library.

[tablesaw]: https://github.com/filamentgroup/tablesaw

## Installation

Add this line to your application's Gemfile:

    gem 'tablesaw-rails'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install tablesaw-rails

## Usage

In your `application.js`:

```javascript
//= require tablesaw/tables
```

Also, in your `application.css`:
```css
*= require tablesaw/tables
```

## Customization

You can also just cherry pick what you want on the tablesaw plugins.

#### Javascript

  ```
  //= require tablesaw/tables.sortable
  //= require tablesaw/tables.columntoggle
  //= require tablesaw/tables.stack
  //= require tablesaw/tables.swipetoggle
  //= require tablesaw/tables.modeswitch
  ```

#### CSS

  ```
  *= require tablesaw/tables.sortable
  *= require tablesaw/tables.columntoggle
  *= require tablesaw/tables.stack
  *= require tablesaw/tables.swipetoggle
  *= require tablesaw/tables.modeswitch
  ```

## Contributing

1. Fork it ( https://github.com/[my-github-username]/tablesaw-rails/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request

## License
[MIT][MIT]. Do what you want.

[MIT]: https://github.com/rbmrclo/tablesaw-rails/blob/master/LICENSE.txt 
