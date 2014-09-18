# PDFtk::Heroku

Adds PDFtk library to your Heroku stack without the need for a custom buildpack.

## Requires Cedar14 Stack

Latest version of PDFtk 2.0.2 requires the [Heroku Cedar14 stack](https://blog.heroku.com/archives/2014/8/19/cedar-14-public-beta) due to certain dependancies only available in the newer releases of Ubuntu.

## Installation

Add this line to your application's Gemfile:

    gem 'pdftk-heroku'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install pdftk-heroku

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
