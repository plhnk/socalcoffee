source "https://rubygems.org"
ruby RUBY_VERSION
# gem 'siteleaf', '2.0.0.pre.beta9'
gem "jekyll", "3.8.3"

require 'rbconfig'
  if RbConfig::CONFIG['target_os'] =~ /darwin(1[0-3])/i
    gem 'rb-fsevent', '<= 0.9.4'
  end