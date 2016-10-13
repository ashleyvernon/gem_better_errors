
# Better Errors [![Gem Version](https://img.shields.io/gem/v/better_errors.svg)](https://rubygems.org/gems/better_errors) [![Build Status](https://travis-ci.org/charliesome/better_errors.svg)](https://travis-ci.org/charliesome/better_errors) [![Code Climate](https://img.shields.io/codeclimate/github/charliesome/better_errors.svg)](https://codeclimate.com/github/charliesome/better_errors)

Better Errors replaces the standard Rails error page with a much better and more useful error page. It is also usable outside of Rails in any Rack app as Rack middleware.

![Imgur](http://i.imgur.com/EF5yzXG.png)

#Installation

Add this to your Gemfile:
```ruby
group :development do
  gem "better_errors"
end
```

There is an optional **advanced features** (local/instance variable inspection, pretty stack frame names)
```ruby
gem "binding_of_caller"
```

**Wait**
_Are you getting an error that Better_Errors isn't working?_
Try adding:
`config.consider_all_requests_local = true` in **`config/environments/development.rb`**
