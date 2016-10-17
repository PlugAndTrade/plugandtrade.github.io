Plug And Trade Website
====================

# Setup

###Install ruby
First check if ruby is installed:
´ruby --version´
This should return a version. If ruby is not installed, download latest ruby.

###Install bundler
´gem install bundler´

On Windows machines this is prone to fail with an ssl cert error.  In that case edit/create ~/.gemrc to look like this and try again:
---
:backtrace: false
:bulk_threshold: 1000
:sources: ["http://rubygems.org"]
:update_sources: true
:verbose: true

###Run bundle install
Go to the project root folder and run
´bundle install´

# Debug
From project root folder run
´bundle exec jekyll serve´

# Release
Just push to master and the changes will be live on https://plugandtrade.github.io/ within moments.

# Theme

Site theme based on [Agency bootstrap theme ](http://startbootstrap.com/templates/agency/)

###Portfolio 

Portfolio projects are in '/_posts'

Images are in '/img/portfolio'

###About

Images are in '/img/about/'

###Team

Team members and info are in '_config.yml'

Images are in '/img/team/'
=========
For more details, read [documentation](http://jekyllrb.com/)
