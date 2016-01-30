SpreeAddToCartAjax
==================

* Adds button 'Add to cart' for each product on Products list page.
* Puts product to cart over AJAX without overloading a page.

Demo: https://spreecommerce-demo.herokuapp.com/

Installation
------------

Add spree_add_to_cart_ajax to your Gemfile:

```ruby
gem 'spree_add_to_cart_ajax'
```

Bundle your dependencies and run the installation generator:

```shell
bundle
bundle exec rails g spree_add_to_cart_ajax:install
```

Testing
-------

First bundle your dependencies, then run `rake`. `rake` will default to building the dummy app if it does not exist, then it will run specs. The dummy app can be regenerated by using `rake test_app`.

```shell
bundle
bundle exec rake
```

When testing your applications integration with this extension you may use it's factories.
Simply add this require statement to your spec_helper:

```ruby
require 'spree_add_to_cart_ajax/factories'
```
