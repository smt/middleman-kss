# Middleman KSS example app

This is my example app of Kyle Neath's [KSS](https://github.com/kneath/kss) ported to Middleman. At this time, KSS 0.1.3 and Middleman 3.0.0.beta.1 are being used.

I also took the opportunity to port the KSS example to Sass+Compass with the HTML5 boilerplate. For more information, please view [my blog post](http://stephentudor.com/blog/2012/01/10/kss-and-middleman).

## Requirements

* ruby 1.9.3
* rvm

## Installation

Be sure to check the Gemfile to make sure it is right for your system. I use a Mac, so `rb-fsevent` is included.

Please also review the .rvmrc file and alter it to taste. When you `cd` to the project root, rvm will create a new gemset for this project and activate it, so as not to pollute your system.

```
$ git clone git://github.com/smt/middleman-kss
$ cd middleman-kss
$ gem install bundler
$ bundle install
$ middleman
```

Lastly, browse to `http://localhost:4567`.