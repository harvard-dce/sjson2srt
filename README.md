# Sjson2srt

This converts sjson to srt files.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'sjson2srt'
```

And then execute:

    $ bundle

Or install it yourself:

    $ gem install sjson2srt

## Usage

In a ruby program:

    srt_content = Sjson2srt::Converter.new(sjson_string).convert

This gem will install an executable named `sjson2srt` suitable for use in a
unix pipeline, thusly:

    cat file.sjson | sjson2srt > output.srt

## Contributing

1. Fork it ( https://github.com/[my-github-username]/sjson2srt/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request

## Contributors

* DJCP

## Copyright

President and Fellows of Harvard College, 2014
