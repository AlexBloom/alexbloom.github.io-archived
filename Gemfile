# A sample Gemfile
source "http://rubygems.org"

require 'rbconfig'
  if RbConfig::CONFIG['target_os'] =~ /darwin(1[0-3])/i
    gem 'rb-fsevent', '<= 0.9.4'
  end

# gem "rails"
gem 'jekyll'
# gem 'jekyll-assets'
# gem 'autoprefixer-rails'

group :jekyll_plugins do
    gem 'jekyll-livereload'
end
